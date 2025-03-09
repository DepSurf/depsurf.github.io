# Function: <code>bdev_direct_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int bdev_direct_access(struct block_device * bdev, sector_t sector, void * * addr, long unsigned int * pfn, long int size)
```

```json
{
  "name": "bdev_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235488,
      "name": "bdev_direct_access",
      "external": true,
      "loc": "fs/block_dev.c:467",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_fault",
        "fs/dax.c:__dax_fault",
        "fs/dax.c:dax_do_io",
        "fs/dax.c:dax_zero_page_range",
        "fs/dax.c:dax_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235488,
      "name": "bdev_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int bdev_direct_access(struct block_device * bdev, struct blk_dax_ctl * dax)
```

```json
{
  "name": "bdev_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401280,
      "name": "bdev_direct_access",
      "external": true,
      "loc": "fs/block_dev.c:482",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_dax_capable",
        "fs/block_dev.c:bdev_dax_capable",
        "fs/dax.c:dax_map_atomic",
        "drivers/md/dm-linear.c:linear_direct_access",
        "drivers/md/dm-stripe.c:stripe_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401280,
      "name": "bdev_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int bdev_direct_access(struct block_device * bdev, struct blk_dax_ctl * dax)
```

```json
{
  "name": "bdev_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479616,
      "name": "bdev_direct_access",
      "external": true,
      "loc": "fs/block_dev.c:734",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_dax_capable",
        "fs/block_dev.c:bdev_dax_capable",
        "fs/dax.c:dax_map_atomic",
        "drivers/md/dm-linear.c:linear_direct_access",
        "drivers/md/dm-stripe.c:stripe_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479616,
      "name": "bdev_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_dax_ctl * dax</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t sector</code>
</li>
<li>
<b>Param removed. </b>
<code>void * * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long int size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
long int bdev_direct_access(struct block_device * bdev, struct blk_dax_ctl * dax)
```
</details>
</li>
</ul>

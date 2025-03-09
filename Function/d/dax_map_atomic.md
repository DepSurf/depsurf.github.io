# Function: <code>dax_map_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int dax_map_atomic(struct block_device * bdev, struct blk_dax_ctl * dax)
```

```json
{
  "name": "dax_map_atomic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493296,
      "name": "dax_map_atomic",
      "external": false,
      "loc": "fs/dax.c:73",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_do_io",
        "fs/dax.c:read_dax_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493296,
      "name": "dax_map_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
long int dax_map_atomic(struct block_device * bdev, struct blk_dax_ctl * dax)
```

```json
{
  "name": "dax_map_atomic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575104,
      "name": "dax_map_atomic",
      "external": false,
      "loc": "fs/dax.c:54",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:read_dax_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575104,
      "name": "dax_map_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long int dax_map_atomic(struct block_device * bdev, struct blk_dax_ctl * dax)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
long int dax_map_atomic(struct block_device * bdev, struct blk_dax_ctl * dax)
```
</details>
</li>
</ul>

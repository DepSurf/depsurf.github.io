# Function: <code>mmc_blk_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_blk_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501428376,
      "name": "mmc_blk_get",
      "external": false,
      "loc": "drivers/mmc/core/block.c:172",
      "file": "drivers/mmc/core/block.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_open",
        "drivers/mmc/core/block.c:mmc_blk_open",
        "drivers/mmc/core/block.c:force_ro_store",
        "drivers/mmc/core/block.c:force_ro_show",
        "drivers/mmc/core/block.c:power_ro_lock_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501428376,
      "name": "mmc_blk_get.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmc_blk_data * mmc_blk_get(struct gendisk * disk)
```

```json
{
  "name": "mmc_blk_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233913892,
      "name": "mmc_blk_get",
      "external": false,
      "loc": "drivers/mmc/core/block.c:172",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_open",
        "drivers/mmc/core/block.c:mmc_blk_open",
        "drivers/mmc/core/block.c:force_ro_store",
        "drivers/mmc/core/block.c:force_ro_show",
        "drivers/mmc/core/block.c:power_ro_lock_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233913892,
      "name": "mmc_blk_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mmc_blk_data * mmc_blk_get(struct gendisk * disk)
```

```json
{
  "name": "mmc_blk_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278029104,
      "name": "mmc_blk_get",
      "external": false,
      "loc": "drivers/mmc/core/block.c:172",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_open",
        "drivers/mmc/core/block.c:mmc_blk_open",
        "drivers/mmc/core/block.c:force_ro_store",
        "drivers/mmc/core/block.c:force_ro_show",
        "drivers/mmc/core/block.c:power_ro_lock_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278029104,
      "name": "mmc_blk_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct mmc_blk_data * mmc_blk_get(struct gendisk * disk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct mmc_blk_data * mmc_blk_get(struct gendisk * disk)
```
</details>
</li>
</ul>

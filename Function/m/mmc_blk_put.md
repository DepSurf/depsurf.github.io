# Function: <code>mmc_blk_put</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void mmc_blk_put(struct mmc_blk_data * md)
```

```json
{
  "name": "mmc_blk_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501425664,
      "name": "mmc_blk_put",
      "external": false,
      "loc": "drivers/mmc/core/block.c:193",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_release",
        "drivers/mmc/core/block.c:mmc_blk_release",
        "drivers/mmc/core/block.c:mmc_blk_open",
        "drivers/mmc/core/block.c:force_ro_store",
        "drivers/mmc/core/block.c:force_ro_show",
        "drivers/mmc/core/block.c:power_ro_lock_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501425664,
      "name": "mmc_blk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void mmc_blk_put(struct mmc_blk_data * md)
```

```json
{
  "name": "mmc_blk_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233914184,
      "name": "mmc_blk_put",
      "external": false,
      "loc": "drivers/mmc/core/block.c:193",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_release",
        "drivers/mmc/core/block.c:mmc_blk_release",
        "drivers/mmc/core/block.c:mmc_blk_open",
        "drivers/mmc/core/block.c:force_ro_store",
        "drivers/mmc/core/block.c:force_ro_show",
        "drivers/mmc/core/block.c:power_ro_lock_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233914184,
      "name": "mmc_blk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void mmc_blk_put(struct mmc_blk_data * md)
```

```json
{
  "name": "mmc_blk_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278029348,
      "name": "mmc_blk_put",
      "external": false,
      "loc": "drivers/mmc/core/block.c:193",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_release",
        "drivers/mmc/core/block.c:mmc_blk_release",
        "drivers/mmc/core/block.c:mmc_blk_open",
        "drivers/mmc/core/block.c:force_ro_store",
        "drivers/mmc/core/block.c:force_ro_show",
        "drivers/mmc/core/block.c:power_ro_lock_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278029348,
      "name": "mmc_blk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void mmc_blk_put(struct mmc_blk_data * md)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mmc_blk_put(struct mmc_blk_data * md)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void mmc_blk_put(struct mmc_blk_data * md)
```
</details>
</li>
</ul>

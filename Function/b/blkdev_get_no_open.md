# Function: <code>blkdev_get_no_open</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```

```json
{
  "name": "blkdev_get_no_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443664,
      "name": "blkdev_get_no_open",
      "external": true,
      "loc": "fs/block_dev.c:1359",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443664,
      "name": "blkdev_get_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```

```json
{
  "name": "blkdev_get_no_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470560,
      "name": "blkdev_get_no_open",
      "external": true,
      "loc": "fs/block_dev.c:1369",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470560,
      "name": "blkdev_get_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```

```json
{
  "name": "blkdev_get_no_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584893776,
      "name": "blkdev_get_no_open",
      "external": true,
      "loc": "block/bdev.c:732",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893776,
      "name": "blkdev_get_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```

```json
{
  "name": "blkdev_get_no_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_get_no_open",
      "external": true,
      "loc": "block/bdev.c:737",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095161,
      "name": "blkdev_get_no_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585592752,
      "name": "blkdev_get_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```

```json
{
  "name": "blkdev_get_no_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586359664,
      "name": "blkdev_get_no_open",
      "external": true,
      "loc": "block/bdev.c:736",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_statx_dioalign",
        "block/blk-cgroup.c:blkcg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586359664,
      "name": "blkdev_get_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```

```json
{
  "name": "blkdev_get_no_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606000,
      "name": "blkdev_get_no_open",
      "external": true,
      "loc": "block/bdev.c:719",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_statx_dioalign",
        "block/blk-cgroup.c:blkg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606000,
      "name": "blkdev_get_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```

```json
{
  "name": "blkdev_get_no_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875376,
      "name": "blkdev_get_no_open",
      "external": true,
      "loc": "block/bdev.c:710",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_statx_dioalign",
        "block/bdev.c:bdev_open_by_dev",
        "block/bdev.c:bdev_open_by_dev",
        "block/blk-cgroup.c:blkg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875376,
      "name": "blkdev_get_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct block_device * blkdev_get_no_open(dev_t dev)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

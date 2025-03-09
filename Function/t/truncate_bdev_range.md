# Function: <code>truncate_bdev_range</code>

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
int truncate_bdev_range(struct block_device * bdev, fmode_t mode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_bdev_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442176,
      "name": "truncate_bdev_range",
      "external": true,
      "loc": "fs/block_dev.c:110",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442176,
      "name": "truncate_bdev_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int truncate_bdev_range(struct block_device * bdev, fmode_t mode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_bdev_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469072,
      "name": "truncate_bdev_range",
      "external": true,
      "loc": "fs/block_dev.c:110",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469072,
      "name": "truncate_bdev_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int truncate_bdev_range(struct block_device * bdev, fmode_t mode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_bdev_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892176,
      "name": "truncate_bdev_range",
      "external": true,
      "loc": "block/bdev.c:101",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blk_ioctl_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892176,
      "name": "truncate_bdev_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device * bdev, fmode_t mode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_bdev_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585591024,
      "name": "truncate_bdev_range",
      "external": true,
      "loc": "block/bdev.c:97",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585591024,
      "name": "truncate_bdev_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int truncate_bdev_range(struct block_device * bdev, fmode_t mode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_bdev_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586357728,
      "name": "truncate_bdev_range",
      "external": true,
      "loc": "block/bdev.c:96",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357728,
      "name": "truncate_bdev_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int truncate_bdev_range(struct block_device * bdev, blk_mode_t mode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_bdev_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586604336,
      "name": "truncate_bdev_range",
      "external": true,
      "loc": "block/bdev.c:96",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586604336,
      "name": "truncate_bdev_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int truncate_bdev_range(struct block_device * bdev, blk_mode_t mode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_bdev_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586873440,
      "name": "truncate_bdev_range",
      "external": true,
      "loc": "block/bdev.c:99",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586873440,
      "name": "truncate_bdev_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int truncate_bdev_range(struct block_device * bdev, fmode_t mode, loff_t lstart, loff_t lend)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

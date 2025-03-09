# Function: <code>blkdev_common_ioctl</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int blkdev_common_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584447872,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:494",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447872,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2097
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int blkdev_common_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564096,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:453",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564096,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2096
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
int blkdev_common_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597008,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:455",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597008,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2095
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
int blkdev_common_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012128,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:468",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012128,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2183
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
int blkdev_common_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:470",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727664,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2454
    },
    {
      "addr": 18446744071594099399,
      "name": "blkdev_common_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int blkdev_common_ioctl(struct file * file, fmode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:470",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508912,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2491
    },
    {
      "addr": 18446744071596107912,
      "name": "blkdev_common_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int blkdev_common_ioctl(struct block_device * bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:487",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586755376,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2454
    },
    {
      "addr": 18446744071596631818,
      "name": "blkdev_common_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int blkdev_common_ioctl(struct block_device * bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```

```json
{
  "name": "blkdev_common_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_common_ioctl",
      "external": false,
      "loc": "block/ioctl.c:498",
      "file": "block/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027600,
      "name": "blkdev_common_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2515
    },
    {
      "addr": 18446744071597538351,
      "name": "blkdev_common_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int blkdev_common_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg, void * argp)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device * bdev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * file</code>
</li>
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

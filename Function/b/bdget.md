# Function: <code>bdget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235696,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:627",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235696,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401536,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:705",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401536,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479872,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:957",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479872,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534864,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:873",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:bd_acquire",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534864,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677424,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:863",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:bd_acquire",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677424,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846320,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:864",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846320,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935600,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:903",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935600,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073744,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073744,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149888,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149888,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582387872,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:881",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:bd_acquire",
        "block/genhd.c:bdget_disk",
        "block/partitions/core.c:bdev_resize_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387872,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582443697,
      "name": "bdget",
      "external": false,
      "loc": "fs/block_dev.c:919",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_no_open",
        "fs/block_dev.c:blkdev_get_no_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582470565,
      "name": "bdget",
      "external": false,
      "loc": "fs/block_dev.c:925",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_no_open",
        "fs/block_dev.c:blkdev_get_no_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493702168,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:bd_acquire",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493702168,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227221316,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:bd_acquire",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227221316,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287294624,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:bd_acquire",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287294624,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273318130,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273318130,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118624,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118624,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056064,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056064,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109104,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109104,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct block_device * bdget(dev_t dev)
```

```json
{
  "name": "bdget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175632,
      "name": "bdget",
      "external": true,
      "loc": "fs/block_dev.c:900",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "fs/block_dev.c:blkdev_get_by_dev",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175632,
      "name": "bdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct block_device * bdget(dev_t dev)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

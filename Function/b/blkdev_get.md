# Function: <code>blkdev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241344,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1340",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241344,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408032,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1412",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408032,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487488,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1658",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487488,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542416,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1585",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542416,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685280,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1576",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SYSC_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685280,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848704,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1600",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848704,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936224,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1633",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936224,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074544,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1692",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074544,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582153232,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153232,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582389424,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1713",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:get_swap_writer",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:register_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389424,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493705464,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493705464,
      "name": "blkdev_get",
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227233084,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227233084,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287310000,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287310000,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273321496,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273321496,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582121968,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121968,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059408,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059408,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112448,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112448,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
```

```json
{
  "name": "blkdev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582185408,
      "name": "blkdev_get",
      "external": true,
      "loc": "fs/block_dev.c:1695",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get_by_dev",
        "fs/block_dev.c:blkdev_get_by_path",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185408,
      "name": "blkdev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_get(struct block_device * bdev, fmode_t mode, void * holder)
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

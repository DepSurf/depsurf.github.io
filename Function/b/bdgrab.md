# Function: <code>bdgrab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581236400,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:666",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": [
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:SyS_swapon",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236400,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581408497,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:744",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402368,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581487948,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:996",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482192,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581542536,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:912",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire"
      ],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537232,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581685402,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:902",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire"
      ],
      "caller_func": [
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679904,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581848844,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:903",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841216,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936364,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:942",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928768,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582074164,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067776,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582150308,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145408,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582389044,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:920",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_bszset",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379840,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440929,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:936",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_part_iter_next",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_closing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435104,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582468075,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:942",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": [
        "block/genhd.c:blk_lookup_devt",
        "block/partitions/core.c:blk_drop_partitions",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582462032,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493700648,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493694200,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227228888,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227223872,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287305628,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287296512,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273318544,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273312688,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582119044,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114144,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582056484,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051584,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582109524,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104624,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
```

```json
{
  "name": "bdgrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582182463,
      "name": "bdgrab",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_start_claiming"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177808,
      "name": "bdgrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct block_device * bdgrab(struct block_device * bdev)
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

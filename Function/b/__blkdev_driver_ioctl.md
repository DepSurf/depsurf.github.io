# Function: <code>__blkdev_driver_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582812256,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:282",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812256,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583093682,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:282",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091392,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583206075,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:291",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "block/compat_ioctl.c:compat_fd_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202720,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583264238,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:291",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260912,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583443859,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:297",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440416,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583654464,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:297",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651648,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583760889,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:297",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757808,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583949607,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947168,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584053111,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050688,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584450210,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:218",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_common_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446816,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495893080,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495887864,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229237036,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229232440,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290097308,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290092640,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275010978,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275008330,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584021847,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584019424,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583957655,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955232,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005607,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003184,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__blkdev_driver_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584108023,
      "name": "__blkdev_driver_ioctl",
      "external": true,
      "loc": "block/ioctl.c:298",
      "file": "block/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105600,
      "name": "__blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int __blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
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

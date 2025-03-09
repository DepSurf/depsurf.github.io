# Function: <code>set_blocksize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234176,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:104",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "fs/ext4/super.c:ext4_load_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234176,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400256,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:117",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400256,
      "name": "set_blocksize",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478592,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:119",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478592,
      "name": "set_blocksize",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539280,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:119",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539280,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682000,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "fs/ext4/super.c:ext4_load_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682000,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839856,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_load_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839856,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927232,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_load_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927232,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064832,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064832,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142496,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142496,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384768,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:120",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:get_swap_writer",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/block_dev.c:sb_min_blocksize",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384768,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439424,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:153",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_swap_check",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/block_dev.c:sb_min_blocksize",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439424,
      "name": "set_blocksize",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466544,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:152",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/block_dev.c:sb_min_blocksize",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466544,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890752,
      "name": "set_blocksize",
      "external": true,
      "loc": "block/bdev.c:143",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/bdev.c:sb_min_blocksize",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890752,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585591248,
      "name": "set_blocksize",
      "external": true,
      "loc": "block/bdev.c:139",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/bdev.c:sb_min_blocksize",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585591248,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586357968,
      "name": "set_blocksize",
      "external": true,
      "loc": "block/bdev.c:138",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/bdev.c:sb_min_blocksize",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357968,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586604576,
      "name": "set_blocksize",
      "external": true,
      "loc": "block/bdev.c:138",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/bdev.c:sb_min_blocksize",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586604576,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586873680,
      "name": "set_blocksize",
      "external": true,
      "loc": "block/bdev.c:141",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_journal_blkdev",
        "block/bdev.c:sb_min_blocksize",
        "block/ioctl.c:blkdev_bszset",
        "block/ioctl.c:blkdev_bszset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586873680,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493692384,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493692384,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227220200,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227220200,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287292928,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287292928,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273310766,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273310766,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111232,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111232,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048672,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048672,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101712,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101712,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int set_blocksize(struct block_device * bdev, int size)
```

```json
{
  "name": "set_blocksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582174576,
      "name": "set_blocksize",
      "external": true,
      "loc": "fs/block_dev.c:121",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174576,
      "name": "set_blocksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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

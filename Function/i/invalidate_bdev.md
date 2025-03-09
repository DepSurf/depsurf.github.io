# Function: <code>invalidate_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234048,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:87",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_remount_sb",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234048,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400128,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:100",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_remount_sb",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400128,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478464,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:102",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_remount_sb",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478464,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534128,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:103",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_remount_sb",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534128,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676656,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_remount_sb",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676656,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839728,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_remount_sb",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839728,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927104,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_remount_sb",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927104,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064704,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064704,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142368,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142368,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378800,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:90",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change",
        "fs/block_dev.c:check_disk_size_change",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/partitions/core.c:blk_drop_partitions",
        "block/partitions/core.c:bdev_del_partition",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl_reset",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378800,
      "name": "invalidate_bdev",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434032,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:90",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/partitions/core.c:blk_drop_partitions",
        "block/partitions/core.c:bdev_del_partition",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl_reset",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434032,
      "name": "invalidate_bdev",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460976,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:90",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:bdev_disk_changed",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460976,
      "name": "invalidate_bdev",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584889728,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "block/bdev.c:81",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bdev.c:__invalidate_device",
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584889728,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585589861,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "block/bdev.c:81",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:__invalidate_device"
      ],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/genhd.c:invalidate_disk",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585588416,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586356533,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "block/bdev.c:80",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:__invalidate_device"
      ],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/genhd.c:invalidate_disk",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586354896,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586603173,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "block/bdev.c:80",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:__invalidate_device"
      ],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/genhd.c:invalidate_disk",
        "block/partitions/core.c:bdev_disk_changed",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601536,
      "name": "invalidate_bdev",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586874301,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "block/bdev.c:83",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_mark_dead"
      ],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/genhd.c:invalidate_disk",
        "block/partitions/core.c:bdev_disk_changed",
        "block/partitions/core.c:bdev_disk_changed",
        "block/partitions/core.c:bdev_del_partition",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586870848,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493692208,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493692208,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227220056,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227220056,
      "name": "invalidate_bdev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287292656,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287292656,
      "name": "invalidate_bdev",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273310614,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273310614,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111104,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111104,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048544,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048544,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101584,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101584,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void invalidate_bdev(struct block_device * bdev)
```

```json
{
  "name": "invalidate_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582174448,
      "name": "invalidate_bdev",
      "external": true,
      "loc": "fs/block_dev.c:91",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:reconfigure_super",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174448,
      "name": "invalidate_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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

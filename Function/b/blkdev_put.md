# Function: <code>blkdev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240512,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1577",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapon",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240512,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405840,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1649",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405840,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487104,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1895",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487104,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581541232,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1817",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541232,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684096,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1810",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684096,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848384,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1831",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848384,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935904,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1864",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935904,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073408,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1904",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073408,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149616,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149616,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388192,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1919",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:get_swap_writer",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:register_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388192,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441296,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1596",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_swap_check",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:register_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441296,
      "name": "blkdev_put",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468368,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1593",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:register_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468368,
      "name": "blkdev_put",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_put",
      "external": true,
      "loc": "block/bdev.c:897",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bdev.c:blkdev_get_by_path",
        "block/fops.c:blkdev_close",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592312482,
      "name": "blkdev_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584892416,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_put",
      "external": true,
      "loc": "block/bdev.c:898",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bdev.c:blkdev_get_by_path",
        "block/fops.c:blkdev_close",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:disk_scan_partitions",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095140,
      "name": "blkdev_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585590544,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_put",
      "external": true,
      "loc": "block/bdev.c:897",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bdev.c:blkdev_get_by_path",
        "block/fops.c:blkdev_close",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:disk_scan_partitions",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596104300,
      "name": "blkdev_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586357216,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void blkdev_put(struct block_device * bdev, void * holder)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_put",
      "external": true,
      "loc": "block/bdev.c:887",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bdev.c:blkdev_get_by_path",
        "block/fops.c:blkdev_release",
        "block/ioctl.c:blkdev_bszset",
        "block/genhd.c:disk_scan_partitions",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596628068,
      "name": "blkdev_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586603840,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
    }
  ]
}
```
</details>
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493701800,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493701800,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227225336,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227225336,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287298288,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287298288,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273317812,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273317812,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118352,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118352,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055792,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055792,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582108832,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108832,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void blkdev_put(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178992,
      "name": "blkdev_put",
      "external": true,
      "loc": "fs/block_dev.c:1888",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/super.c:kill_block_super",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/ioctl.c:blkdev_ioctl",
        "block/genhd.c:__device_add_disk",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/dm.c:dm_put_table_device",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178992,
      "name": "blkdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * holder</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void blkdev_put(struct block_device * bdev, void * holder)
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

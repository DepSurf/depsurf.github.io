# Function: <code>inode_dio_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103152,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:1996",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103152,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268816,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2013",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268816,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346688,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2063",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346688,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402128,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2053",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402128,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543760,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2066",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543760,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698160,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2064",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698160,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784512,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2071",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784512,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902704,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2109",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902704,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974944,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974944,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207200,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2204",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207200,
      "name": "inode_dio_wait",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254672,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2205",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254672,
      "name": "inode_dio_wait",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280576,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2231",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280576,
      "name": "inode_dio_wait",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598624,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2236",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598624,
      "name": "inode_dio_wait",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583131568,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2317",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131568,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701984,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2366",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701984,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919408,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2411",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919408,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584125392,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2414",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_checks",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125392,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493480872,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493480872,
      "name": "inode_dio_wait",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227045816,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227045816,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287041824,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287041824,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273158442,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273158442,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943680,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943680,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881248,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881248,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934992,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934992,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void inode_dio_wait(struct inode * inode)
```

```json
{
  "name": "inode_dio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582006432,
      "name": "inode_dio_wait",
      "external": true,
      "loc": "fs/inode.c:2120",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006432,
      "name": "inode_dio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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

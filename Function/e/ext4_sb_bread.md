# Function: <code>ext4_sb_bread</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630400,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:155",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630400,
      "name": "ext4_sb_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582803040,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:156",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803040,
      "name": "ext4_sb_bread",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906400,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906400,
      "name": "ext4_sb_bread",
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583220064,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_tind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220064,
      "name": "ext4_sb_bread",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322032,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:234",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_tind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322032,
      "name": "ext4_sb_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344848,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:234",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344848,
      "name": "ext4_sb_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687552,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:231",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687552,
      "name": "ext4_sb_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237968,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:250",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237968,
      "name": "ext4_sb_bread",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, blk_opf_t op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584882192,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584882192,
      "name": "ext4_sb_bread",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, blk_opf_t op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585109392,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585109392,
      "name": "ext4_sb_bread",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, blk_opf_t op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341728,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:244",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341728,
      "name": "ext4_sb_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494581080,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494581080,
      "name": "ext4_sb_bread",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228024312,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228024312,
      "name": "ext4_sb_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288379120,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288379120,
      "name": "ext4_sb_bread",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273961104,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273961104,
      "name": "ext4_sb_bread",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875136,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875136,
      "name": "ext4_sb_bread",
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812288,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812288,
      "name": "ext4_sb_bread",
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582864016,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864016,
      "name": "ext4_sb_bread",
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
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```

```json
{
  "name": "ext4_sb_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950688,
      "name": "ext4_sb_bread",
      "external": true,
      "loc": "fs/ext4/super.c:151",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950688,
      "name": "ext4_sb_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct buffer_head * ext4_sb_bread(struct super_block * sb, sector_t block, int op_flags)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int op_flags</code> ➡️ <code>blk_opf_t op_flags</code>
</li>
</ul>
</details>
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

# Function: <code>__ext4_handle_dirty_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777264,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:253",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777264,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972128,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:253",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972128,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062160,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:253",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062160,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885776,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:264",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885776,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035808,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:265",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035808,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224680,
      "name": "__ext4_handle_dirty_metadata.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582224096,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319576,
      "name": "__ext4_handle_dirty_metadata.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582318992,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486695,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582486064,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585932,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582585328,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:320",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895356,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071582894720,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:320",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_update_super_block",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346907,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071582966976,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:320",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289737,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071582993024,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:338",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/orphan.c:ext4_orphan_file_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250961,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071583329488,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:338",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/orphan.c:ext4_orphan_file_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594031982,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071583838176,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584461680,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:343",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:write_end_fn",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/orphan.c:ext4_orphan_file_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584461680,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690576,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:343",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:write_end_fn",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/orphan.c:ext4_orphan_file_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690576,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584923264,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:342",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:write_end_fn",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_handle_dirty_dx_node",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/orphan.c:ext4_orphan_file_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923264,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494234992,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494234992,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227665220,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227665220,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287935008,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287935008,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273687756,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273687756,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554668,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582554064,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491836,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582491232,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544780,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582544176,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __ext4_handle_dirty_metadata(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_handle_dirty_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_handle_dirty_metadata",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:258",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625900,
      "name": "__ext4_handle_dirty_metadata.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582625296,
      "name": "__ext4_handle_dirty_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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

# Function: <code>__ext4_journal_get_write_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776560,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:156",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
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
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_delete_inline_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776560,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971424,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:156",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971424,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061440,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:156",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061440,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885056,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:160",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/file.c:ext4_file_open",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885056,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035088,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/file.c:ext4_file_open",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035088,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223408,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223408,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318304,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318304,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485376,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485376,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584640,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584640,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582894080,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:220",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents_endio",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/file.c:ext4_sample_last_mounted",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894080,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966352,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:220",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents_endio",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/file.c:ext4_sample_last_mounted",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_update_super_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966352,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582992256,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:220",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992256,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328480,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:222",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/orphan.c:ext4_orphan_file_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328480,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837024,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:222",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_get_access",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
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
      "addr": 18446744071583837024,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584460480,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:228",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_get_access",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
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
      "addr": 18446744071584460480,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689376,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:228",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_get_access",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
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
      "addr": 18446744071584689376,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584922112,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:229",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_get_access",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
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
      "addr": 18446744071584922112,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494234136,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494234136,
      "name": "__ext4_journal_get_write_access",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227664476,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227664476,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287933904,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287933904,
      "name": "__ext4_journal_get_write_access",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273687132,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273687132,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582553376,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582553376,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490544,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490544,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543488,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543488,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __ext4_journal_get_write_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_write_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624624,
      "name": "__ext4_journal_get_write_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:161",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
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
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624624,
      "name": "__ext4_journal_get_write_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct super_block * sb</code>
</li>
<li>
<b>Param added. </b>
<code>enum ext4_journal_trigger_type trigger_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>where, line, handle, bh</code> ➡️ <code>where, line, handle, sb, bh, trigger_type</code>
</li>
</ul>
</details>
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

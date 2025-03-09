# Function: <code>__ext4_mark_inode_dirty</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021840,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5811",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021840,
      "name": "__ext4_mark_inode_dirty",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097424,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5904",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_replay_del_range",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097424,
      "name": "__ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122448,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5901",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122448,
      "name": "__ext4_mark_inode_dirty",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463312,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5842",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463312,
      "name": "__ext4_mark_inode_dirty",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986688,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5920",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986688,
      "name": "__ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615872,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6064",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615872,
      "name": "__ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584842608,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5876",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584842608,
      "name": "__ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585075472,
      "name": "__ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5896",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585075472,
      "name": "__ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __ext4_mark_inode_dirty(handle_t * handle, struct inode * inode, const char * func, unsigned int line)
```
</details>
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

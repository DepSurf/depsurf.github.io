# Function: <code>ext4_mark_inode_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579280,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5102",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/crypto_policy.c:ext4_process_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579280,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766208,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5443",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/acl.c:__ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766208,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855360,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5587",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/acl.c:__ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855360,
      "name": "ext4_mark_inode_dirty",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003376,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5838",
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
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003376,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582153376,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5891",
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
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153376,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340928,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5987",
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
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340928,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440048,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6040",
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
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440048,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609552,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6062",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609552,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710464,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710464,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494368144,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494368144,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227802452,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_update_dir_count",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227802452,
      "name": "ext4_mark_inode_dirty",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288100928,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_writepages",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288100928,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273795508,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273795508,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582679200,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582679200,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616368,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616368,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669056,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669056,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582752832,
      "name": "ext4_mark_inode_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:6091",
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
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_tree_init",
        "fs/ext4/extents.c:__ext4_ext_dirty",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
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
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
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
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752832,
      "name": "ext4_mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int ext4_mark_inode_dirty(handle_t * handle, struct inode * inode)
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

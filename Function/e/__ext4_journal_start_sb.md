# Function: <code>__ext4_journal_start_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775824,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:62",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto_policy.c:ext4_process_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775824,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970704,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:62",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970704,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582060720,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:62",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060720,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884304,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:66",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884304,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034336,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034336,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222656,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222656,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317552,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317552,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484624,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484624,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583888,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583888,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582893136,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:89",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582893136,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965488,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:89",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965488,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582991392,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:89",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991392,
      "name": "__ext4_journal_start_sb",
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327584,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:89",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327584,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835920,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:89",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835920,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
handle_t * __ext4_journal_start_sb(struct inode * inode, struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584459184,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:89",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459184,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
handle_t * __ext4_journal_start_sb(struct inode * inode, struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584688080,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:89",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688080,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
handle_t * __ext4_journal_start_sb(struct inode * inode, struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks, int revoke_creds)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920816,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:90",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920816,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494233232,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494233232,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227663692,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227663692,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287932800,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287932800,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273686488,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273686488,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552624,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552624,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489792,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489792,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542736,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542736,
      "name": "__ext4_journal_start_sb",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
handle_t * __ext4_journal_start_sb(struct super_block * sb, unsigned int line, int type, int blocks, int rsv_blocks)
```

```json
{
  "name": "__ext4_journal_start_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582623840,
      "name": "__ext4_journal_start_sb",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:67",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_dirty_inode",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_update_disksize_before_punch",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_write_info",
        "fs/ext4/super.c:ext4_release_dquot",
        "fs/ext4/super.c:ext4_acquire_dquot",
        "fs/ext4/super.c:ext4_write_dquot",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623840,
      "name": "__ext4_journal_start_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int revoke_creds</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, line, type, blocks, rsv_blocks, revoke_creds</code> ➡️ <code>inode, sb, line, type, blocks, rsv_blocks, revoke_creds</code>
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

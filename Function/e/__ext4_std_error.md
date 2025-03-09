# Function: <code>__ext4_std_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698048,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:538",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_delete_inline_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698048,
      "name": "__ext4_std_error",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890192,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:567",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890192,
      "name": "__ext4_std_error",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979392,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:569",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979392,
      "name": "__ext4_std_error",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582195584,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:583",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195584,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344304,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:583",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344304,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582533536,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:589",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533536,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634624,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:631",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634624,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807216,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:642",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807216,
      "name": "__ext4_std_error",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582910576,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582910576,
      "name": "__ext4_std_error",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583225312,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_orphan_cleanup",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225312,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327056,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:869",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_orphan_cleanup",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327056,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583349504,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:878",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_orphan_cleanup",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349504,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583693568,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:877",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693568,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244528,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:902",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244528,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584889840,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:895",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584889840,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116992,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:895",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116992,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585349408,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:964",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349408,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494586800,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494586800,
      "name": "__ext4_std_error",
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228029468,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228029468,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288385696,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288385696,
      "name": "__ext4_std_error",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273965538,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273965538,
      "name": "__ext4_std_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879312,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879312,
      "name": "__ext4_std_error",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816464,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816464,
      "name": "__ext4_std_error",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582868192,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868192,
      "name": "__ext4_std_error",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block * sb, const char * function, unsigned int line, int errno)
```

```json
{
  "name": "__ext4_std_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582954896,
      "name": "__ext4_std_error",
      "external": true,
      "loc": "fs/ext4/super.c:637",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_stop",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954896,
      "name": "__ext4_std_error",
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

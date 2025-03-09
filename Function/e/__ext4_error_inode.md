# Function: <code>__ext4_error_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697248,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:428",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/crypto_policy.c:ext4_process_policy",
        "fs/ext4/crypto_fname.c:_ext4_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697248,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888992,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:457",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/inline.c:empty_inline_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888992,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978048,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:459",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/inline.c:empty_inline_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978048,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582194240,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:467",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194240,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342896,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:467",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342896,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:471",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562576,
      "name": "__ext4_error_inode.cold.136",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071582532288,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:513",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663792,
      "name": "__ext4_error_inode.cold.140",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071582633376,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:524",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836370,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582805968,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940497,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582909328,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:558",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_dx_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254552,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583223984,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:757",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_get_inode_loc",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_dx_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591347894,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071583325904,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:766",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_get_inode_loc",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591290728,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071583348352,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:765",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc_noinmem",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592269992,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071583692416,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:786",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc_noinmem",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594051457,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584243600,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584888528,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:779",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc_noinmem",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/xattr.c:__ext4_xattr_check_block",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584888528,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585115680,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:779",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inline.c:get_max_inline_xattr_value_size",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc_noinmem",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115680,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585348096,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:848",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_search_left",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_ext_insert_index",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inline.c:get_max_inline_xattr_value_size",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc_noinmem",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:ext4_handle_dirty_dx_node",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348096,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494585120,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494585120,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228027828,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228027828,
      "name": "__ext4_error_inode",
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288383568,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288383568,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273964302,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273964302,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909233,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582878064,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846385,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582815216,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897841,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582866944,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __ext4_error_inode(struct inode * inode, const char * function, unsigned int line, ext4_fsblk_t block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error_inode",
      "external": true,
      "loc": "fs/ext4/super.c:519",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/dir.c:__ext4_check_dir_entry",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_right",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_data",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:xattr_find_entry",
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984929,
      "name": "__ext4_error_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071582953600,
      "name": "__ext4_error_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
<code>int error</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, function, line, block, fmt, (anon)</code> ➡️ <code>inode, function, line, block, error, fmt, (anon)</code>
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

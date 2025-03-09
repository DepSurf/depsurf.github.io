# Function: <code>ext4_free_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812240,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4654",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812240,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2989
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008032,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4661",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008032,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2972
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098080,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4668",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098080,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2983
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062256,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4733",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062256,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2902
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211872,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4733",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211872,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2724
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582401936,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4703",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401936,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2636
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582500928,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4702",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500928,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2899
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582672064,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4704",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672064,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2718
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582774064,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582774064,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2737
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583085504,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4968",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_tind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085504,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2818
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164464,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5249",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/indirect.c:ext4_splice_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_tind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164464,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2758
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191680,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5782",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191680,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2483
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5857",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592264896,
      "name": "ext4_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071583534752,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2408
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069312,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6115",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069312,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584702096,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6084",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702096,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6659",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596602786,
      "name": "ext4_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584925776,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6541",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597508278,
      "name": "ext4_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585157856,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494440528,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494440528,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2452
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227876584,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227876584,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3324
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288192576,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288192576,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3476
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273853270,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273853270,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2390
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742800,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742800,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2737
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582679968,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582679968,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2737
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732656,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732656,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2737
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
void ext4_free_blocks(handle_t * handle, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t block, long unsigned int count, int flags)
```

```json
{
  "name": "ext4_free_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817760,
      "name": "ext4_free_blocks",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4723",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817760,
      "name": "ext4_free_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2876
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

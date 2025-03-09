# Function: <code>ext4_get_inode_loc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581572000,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4019",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_try_to_evict_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572000,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581766067,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4327",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_evict_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758080,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581855219,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4456",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_evict_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846912,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582002799,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4580",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_evict_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996560,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582152799,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4629",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_evict_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146480,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582340355,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4678",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335840,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582439475,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4708",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434768,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582608952,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4720",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604176,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582709864,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704992,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583021224,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4409",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_ibody_list",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016320,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091536,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4451",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_ibody_list",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091536,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583116496,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4450",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116496,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583457280,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4371",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457280,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980208,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4593",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_link",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980208,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584608752,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4688",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_link",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608752,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835232,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4473",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_link",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_folio",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835232,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068096,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4492",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_iomap_xattr_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_link",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_folio",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_get_max_inline_size",
        "fs/ext4/inode.c:ext4_reserve_inode_write",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068096,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494367444,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494362840,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227801868,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227796656,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288099948,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288094384,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273795002,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273790960,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582678600,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673728,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582615768,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610896,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582668456,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663584,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_get_inode_loc(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582752232,
      "name": "ext4_get_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4709",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_reserve_inode_write"
      ],
      "caller_func": [
        "fs/ext4/extents.c:_ext4_fiemap",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_inline_data_fiemap",
        "fs/ext4/inline.c:ext4_inline_data_iomap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inline.c:ext4_get_first_inline_block",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747296,
      "name": "ext4_get_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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

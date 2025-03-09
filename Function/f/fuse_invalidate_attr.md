# Function: <code>fuse_invalidate_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582063355,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:110",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_follow_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_do_setattr"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068096,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582280395,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:112",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282496,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582378734,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:104",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370832,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582463532,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:104",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455296,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582614332,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:104",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606080,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582807154,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:104",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803072,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582900741,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:93",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905920,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583080778,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:93",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085168,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583184910,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185920,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583514878,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510736,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583623761,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:128",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619744,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583652415,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:128",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642432,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584011503,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:128",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999904,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584596725,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:131",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584288,
      "name": "fuse_invalidate_attr",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585275141,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:137",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261744,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585505630,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:137",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492192,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585742322,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728816,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494903252,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494904096,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228325516,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228316340,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288773068,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288768608,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274223360,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274215576,
      "name": "fuse_invalidate_attr",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583153646,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154656,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583090798,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091808,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137678,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138688,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fuse_invalidate_attr(struct inode * inode)
```

```json
{
  "name": "fuse_invalidate_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583231246,
      "name": "fuse_invalidate_attr",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232256,
      "name": "fuse_invalidate_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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

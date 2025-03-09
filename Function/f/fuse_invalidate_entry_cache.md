# Function: <code>fuse_invalidate_entry_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582064503,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:133",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068160,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582287744,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:135",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282560,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582379307,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370896,
      "name": "fuse_invalidate_entry_cache",
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582464247,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455360,
      "name": "fuse_invalidate_entry_cache",
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582615043,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606144,
      "name": "fuse_invalidate_entry_cache",
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582808054,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:127",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803136,
      "name": "fuse_invalidate_entry_cache",
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582910982,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:122",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906000,
      "name": "fuse_invalidate_entry_cache",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583090134,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:122",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085248,
      "name": "fuse_invalidate_entry_cache",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195470,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583186000,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583520316,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510848,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583630071,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:157",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619856,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583653159,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:157",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642544,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584012263,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:157",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000016,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584597636,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:160",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584432,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585276068,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:166",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261904,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585506557,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:166",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492368,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585743309,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/fuse/dir.c:fuse_atomic_open",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728992,
      "name": "fuse_invalidate_entry_cache",
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494913904,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494904248,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228326176,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228316420,
      "name": "fuse_invalidate_entry_cache",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288780788,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288768784,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274224052,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274215696,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583164206,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154736,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583101358,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091888,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583148238,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138768,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void fuse_invalidate_entry_cache(struct dentry * entry)
```

```json
{
  "name": "fuse_invalidate_entry_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241838,
      "name": "fuse_invalidate_entry_cache",
      "external": true,
      "loc": "fs/fuse/dir.c:156",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_setattr",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_lookup"
      ],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232336,
      "name": "fuse_invalidate_entry_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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

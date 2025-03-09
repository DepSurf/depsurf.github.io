# Function: <code>__mb_cache_entry_free</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581567207,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:119",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_block",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566800,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581651815,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:119",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_block",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651408,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581706390,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:120",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705936,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581852022,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:121",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851568,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582032498,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:121",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032000,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582120866,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:121",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120016,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582282770,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281888,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582381428,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380928,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582667092,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666208,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582736052,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735200,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582764692,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763840,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583091284,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090768,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583570905,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569600,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __mb_cache_entry_free(struct mb_cache * cache, struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:127",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596059521,
      "name": "__mb_cache_entry_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584172352,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __mb_cache_entry_free(struct mb_cache * cache, struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:127",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596583664,
      "name": "__mb_cache_entry_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584400208,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __mb_cache_entry_free(struct mb_cache * cache, struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:127",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597488235,
      "name": "__mb_cache_entry_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584620928,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493977384,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493976800,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227442404,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227441832,
      "name": "__mb_cache_entry_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287620484,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287619024,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273498510,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273497488,
      "name": "__mb_cache_entry_free",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582350164,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349664,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582287876,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287376,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582340644,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340144,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```

```json
{
  "name": "__mb_cache_entry_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582419972,
      "name": "__mb_cache_entry_free",
      "external": true,
      "loc": "fs/mbcache.c:122",
      "file": "fs/mbcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419472,
      "name": "__mb_cache_entry_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __mb_cache_entry_free(struct mb_cache_entry * entry)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mb_cache * cache</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry</code> ➡️ <code>cache, entry</code>
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

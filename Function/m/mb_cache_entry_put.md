# Function: <code>mb_cache_entry_put</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581567202,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:32",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_block",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045516,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:32",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581651810,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:32",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_block",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135361,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:32",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581706385,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:32",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238876,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:32",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228800,
      "name": "mb_cache_entry_put.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581852017,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387746,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377152,
      "name": "mb_cache_entry_put.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582032493,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578552,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582120861,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679294,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582282765,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852589,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582381423,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582956749,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582667087,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272625,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582736047,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583373786,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582764687,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396106,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583091279,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583740318,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583570889,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:34",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295548,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:34",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286864,
      "name": "mb_cache_entry_put.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void mb_cache_entry_put(struct mb_cache * cache, struct mb_cache_entry * entry)
```

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584173122,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:48",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584943948,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:48",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930096,
      "name": "mb_cache_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void mb_cache_entry_put(struct mb_cache * cache, struct mb_cache_entry * entry)
```

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584400962,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:48",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585172220,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:48",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158160,
      "name": "mb_cache_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void mb_cache_entry_put(struct mb_cache * cache, struct mb_cache_entry * entry)
```

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584621682,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:48",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585404988,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:48",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585390800,
      "name": "mb_cache_entry_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493977356,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494631780,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227442364,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 3228076988,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287620456,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288440004,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273498510,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274003022,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582350159,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925485,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582287871,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862637,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582340639,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582914093,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mb_cache_entry_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582419967,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001150,
      "name": "mb_cache_entry_put",
      "external": false,
      "loc": "include/linux/mbcache.h:33",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void mb_cache_entry_put(struct mb_cache * cache, struct mb_cache_entry * entry)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

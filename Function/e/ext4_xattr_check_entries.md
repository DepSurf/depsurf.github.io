# Function: <code>ext4_xattr_check_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226800,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:181",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226800,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375104,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:182",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375104,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565760,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565760,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667184,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667184,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839792,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071582861910,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943936,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071582966070,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:185",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258640,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071583281318,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:185",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359568,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071591349037,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:185",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382880,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071591291869,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:185",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727104,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071592271775,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:185",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282352,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071594053526,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930208,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:187",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:__xattr_check_inode",
        "fs/ext4/xattr.c:__ext4_xattr_check_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930208,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494618768,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494618768,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228062836,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228062836,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288423712,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288423712,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273993140,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273993140,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912672,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071582934806,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849824,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071582871958,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901280,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071582923414,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```

```json
{
  "name": "ext4_xattr_check_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_check_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:183",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:__xattr_check_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988352,
      "name": "ext4_xattr_check_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071583010470,
      "name": "ext4_xattr_check_entries.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int ext4_xattr_check_entries(struct ext4_xattr_entry * entry, void * end, void * value_start)
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

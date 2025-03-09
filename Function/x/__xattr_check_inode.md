# Function: <code>__xattr_check_inode</code>

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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582041712,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:235",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_listxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041712,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582131696,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:241",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_listxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131696,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227056,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:243",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227056,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375360,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:244",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375360,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566064,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566064,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667488,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667488,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582840064,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840064,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582944208,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944208,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258912,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:263",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_ibody_list",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258912,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583359840,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:263",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_ibody_list",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359840,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583383152,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:263",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383152,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727376,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:263",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727376,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282656,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:263",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282656,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930544,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:265",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930544,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585181288,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:312",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585414184,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:312",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494619072,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494619072,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228063116,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228063116,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288424128,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288424128,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273993336,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273993336,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912944,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912944,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850096,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850096,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901552,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901552,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
```

```json
{
  "name": "__xattr_check_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582988624,
      "name": "__xattr_check_inode",
      "external": false,
      "loc": "fs/ext4/xattr.c:261",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988624,
      "name": "__xattr_check_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __xattr_check_inode(struct inode * inode, struct ext4_xattr_ibody_header * header, void * end, const char * function, unsigned int line)
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

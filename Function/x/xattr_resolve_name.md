# Function: <code>xattr_resolve_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct xattr_handler * xattr_resolve_name(const struct xattr_handler * * handlers, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145824,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:705",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:generic_getxattr",
        "fs/xattr.c:generic_setxattr",
        "fs/xattr.c:generic_removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145824,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
const struct xattr_handler * xattr_resolve_name(const struct xattr_handler * * handlers, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311440,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:698",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:generic_removexattr",
        "fs/xattr.c:generic_setxattr",
        "fs/xattr.c:generic_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311440,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390656,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:53",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390656,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446000,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:53",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446000,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587936,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587936,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745296,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745296,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831824,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:53",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831824,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956128,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956128,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028832,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028832,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263600,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263600,
      "name": "xattr_resolve_name",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313312,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313312,
      "name": "xattr_resolve_name",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340944,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340944,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661488,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661488,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583201616,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:56",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583201616,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583777888,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:56",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777888,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995136,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:57",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995136,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207840,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:57",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207840,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493553048,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493553048,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227101884,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227101884,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287124144,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287124144,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273213544,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273213544,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997568,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997568,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935136,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935136,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988848,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988848,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
const struct xattr_handler * xattr_resolve_name(struct inode * inode, const char * * name)
```

```json
{
  "name": "xattr_resolve_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059312,
      "name": "xattr_resolve_name",
      "external": false,
      "loc": "fs/xattr.c:54",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr",
        "fs/xattr.c:__vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059312,
      "name": "xattr_resolve_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct xattr_handler * * handlers</code>
</li>
</ul>
</details>
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

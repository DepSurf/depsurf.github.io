# Function: <code>xattr_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146496,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:32",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146496,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311616,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:32",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311616,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391232,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:85",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391232,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446560,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:85",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446560,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588528,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588528,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745888,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745888,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832416,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:85",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832416,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956720,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956720,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029424,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029424,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264192,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264192,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582314128,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314128,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int xattr_permission(struct user_namespace * mnt_userns, struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341760,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341760,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int xattr_permission(struct user_namespace * mnt_userns, struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582662304,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662304,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int xattr_permission(struct user_namespace * mnt_userns, struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202576,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:88",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202576,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
int xattr_permission(struct user_namespace * mnt_userns, struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583782240,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:113",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782240,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int xattr_permission(struct mnt_idmap * idmap, struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998096,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:114",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998096,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int xattr_permission(struct mnt_idmap * idmap, struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210736,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:114",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:__vfs_setxattr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210736,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493553664,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493553664,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227102500,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227102500,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287125056,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287125056,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273214058,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273214058,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998160,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998160,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935728,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935728,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989440,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989440,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int xattr_permission(struct inode * inode, const char * name, int mask)
```

```json
{
  "name": "xattr_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059904,
      "name": "xattr_permission",
      "external": false,
      "loc": "fs/xattr.c:86",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:vfs_getxattr",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059904,
      "name": "xattr_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, name, mask</code> ➡️ <code>mnt_userns, inode, name, mask</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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

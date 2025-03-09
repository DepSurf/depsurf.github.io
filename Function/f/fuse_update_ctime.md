# Function: <code>fuse_update_ctime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582066168,
      "name": "fuse_update_ctime",
      "external": false,
      "loc": "fs/fuse/dir.c:635",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582280391,
      "name": "fuse_update_ctime",
      "external": false,
      "loc": "fs/fuse/dir.c:639",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582369911,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:652",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368000,
      "name": "fuse_update_ctime.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582375824,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582454346,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:652",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452368,
      "name": "fuse_update_ctime.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071582460528,
      "name": "fuse_update_ctime",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582605130,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:652",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603152,
      "name": "fuse_update_ctime.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071582611328,
      "name": "fuse_update_ctime",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582799941,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:653",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796192,
      "name": "fuse_update_ctime.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582804448,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582904993,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:650",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582900016,
      "name": "fuse_update_ctime.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582907296,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583084245,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:637",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080432,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583086496,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583189679,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184176,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583191632,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583514912,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517024,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583623795,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:784",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626048,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583646883,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:801",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649120,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584006595,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:748",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008160,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584592780,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:854",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592288,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585270652,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:877",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271264,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585501127,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:943",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501744,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585738004,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:940",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738624,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494907768,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494900984,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336494909760,
      "name": "fuse_update_ctime",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228320176,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228313456,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 3228322008,
      "name": "fuse_update_ctime",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288773120,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288766000,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055288775536,
      "name": "fuse_update_ctime",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274218730,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274213814,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936274220312,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583158415,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152912,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583160368,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583095567,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090064,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583097520,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583142447,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136944,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583144400,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_update_ctime(struct inode * inode)
```

```json
{
  "name": "fuse_update_ctime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583235997,
      "name": "fuse_update_ctime",
      "external": true,
      "loc": "fs/fuse/dir.c:693",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230896,
      "name": "fuse_update_ctime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583237952,
      "name": "fuse_update_ctime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void fuse_update_ctime(struct inode * inode)
```
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

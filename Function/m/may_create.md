# Function: <code>may_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581041078,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_rename"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265072,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1762",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265072,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581210646,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2812",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489728,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1835",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489728,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581288102,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2776",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582589808,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1843",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589808,
      "name": "may_create",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336042,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2821",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582681616,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1833",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582681616,
      "name": "may_create",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581477066,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2819",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837056,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1847",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837056,
      "name": "may_create",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581644904,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2820",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040368,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1950",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040368,
      "name": "may_create",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581721720,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2839",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583155152,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1764",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155152,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581839504,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2837",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342016,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1808",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342016,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581911968,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583447392,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447392,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582148824,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2732",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790112,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1763",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790112,
      "name": "may_create",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582195021,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2730",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912192,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1772",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912192,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582211582,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2824",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583940320,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1832",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940320,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582529773,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2893",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584306032,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1824",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584306032,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583051291,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2989",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod"
      ]
    },
    {
      "addr": 18446744071584921264,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1762",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047296,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071584921264,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583617547,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2968",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod"
      ]
    },
    {
      "addr": 18446744071585630208,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1761",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612944,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071585630208,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct mnt_idmap * idmap, struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583841814,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2999",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585860176,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1771",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860176,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct mnt_idmap * idmap, struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584048367,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:3016",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586109952,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1811",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109952,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493392632,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495208688,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495208688,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226973976,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 3228587924,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228587924,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286941408,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289151856,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289151856,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273107268,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274442920,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274442920,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581880704,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583416128,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416128,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581818304,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353200,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353200,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581872016,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399904,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399904,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int may_create(struct inode * dir, struct dentry * child)
```

```json
{
  "name": "may_create",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581937358,
      "name": "may_create",
      "external": false,
      "loc": "fs/namei.c:2830",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485760,
      "name": "may_create",
      "external": false,
      "loc": "security/selinux/hooks.c:1810",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mknod",
        "security/selinux/hooks.c:selinux_inode_mkdir",
        "security/selinux/hooks.c:selinux_inode_symlink",
        "security/selinux/hooks.c:selinux_inode_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485760,
      "name": "may_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
<code>dir, child</code> ➡️ <code>mnt_userns, dir, child</code>
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

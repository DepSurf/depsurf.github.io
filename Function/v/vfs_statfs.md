# Function: <code>vfs_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_statfs(struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581211232,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:66",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:user_statfs",
        "fs/statfs.c:fd_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211232,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int vfs_statfs(struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581375904,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:66",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375904,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581453648,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:66",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453648,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581509152,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:69",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509152,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581651776,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:70",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651776,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581814656,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:70",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814656,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581901648,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:70",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901648,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582027184,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027184,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582105120,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105120,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582342843,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341584,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071582341728,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582394363,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:86",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582393072,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071582393248,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582421659,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:86",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420432,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582420560,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582744475,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:86",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs",
        "drivers/block/loop.c:loop_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743248,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582743376,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583291359,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:86",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289888,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071583290032,
      "name": "vfs_statfs",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583875247,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:86",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873552,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071583873712,
      "name": "vfs_statfs",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584097010,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:86",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095312,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584095472,
      "name": "vfs_statfs",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584313154,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:86",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311456,
      "name": "vfs_statfs.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584311616,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493641776,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493641776,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227179612,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227179612,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287234880,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287234880,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273277370,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273277370,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582073856,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073856,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582011408,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011408,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582065136,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065136,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int vfs_statfs(const struct path * path, struct kstatfs * buf)
```

```json
{
  "name": "vfs_statfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582136880,
      "name": "vfs_statfs",
      "external": true,
      "loc": "fs/statfs.c:84",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:check_free_space",
        "fs/statfs.c:fd_statfs",
        "fs/statfs.c:user_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136880,
      "name": "vfs_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
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

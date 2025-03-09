# Function: <code>vfs_get_tree</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1430",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794107,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581785072,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866827,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581857328,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092891,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582082048,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339303,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582128416,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1487",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282019,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582153136,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1487",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592228955,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582470016,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1486",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008512,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582990880,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552192,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1491",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552192,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768704,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1508",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768704,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972864,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1768",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:vfs_cmd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972864,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493326392,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__arm64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493326392,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226922852,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226922852,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286867216,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286867216,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273058662,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273058662,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835563,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581826064,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773227,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581763728,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826875,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581817376,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int vfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "vfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_get_tree",
      "external": true,
      "loc": "fs/super.c:1536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896083,
      "name": "vfs_get_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581887024,
      "name": "vfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int vfs_get_tree(struct fs_context * fc)
```
</details>
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

# Function: <code>__attach_mnt</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364176,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:860",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364176,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419552,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:861",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419552,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561168,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:928",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561168,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717392,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:938",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717392,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804192,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:850",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804192,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581923200,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923200,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995600,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995600,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582229696,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:864",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229696,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582279808,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:864",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279808,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582303472,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:871",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303472,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582625314,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:880",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623040,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071592230515,
      "name": "__attach_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583162498,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:916",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158512,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071594010484,
      "name": "__attach_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583737746,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:1027",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732752,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071596051413,
      "name": "__attach_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:963",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949648,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071596573971,
      "name": "__attach_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:951",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157120,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071597478509,
      "name": "__attach_mnt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493513456,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493513456,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227068080,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227068080,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287076704,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287076704,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273183156,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273183156,
      "name": "__attach_mnt",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581964336,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964336,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901904,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901904,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955616,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955616,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
```

```json
{
  "name": "__attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025824,
      "name": "__attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:848",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:attach_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025824,
      "name": "__attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __attach_mnt(struct mount * mnt, struct mount * parent)
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

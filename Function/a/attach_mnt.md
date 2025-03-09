# Function: <code>attach_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130000,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:862",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130000,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295872,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:862",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:attach_recursive_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295872,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581383718,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:870",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581438975,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:871",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581580863,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:938",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581736814,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:948",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581823502,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:860",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581923328,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
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
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923328,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995728,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
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
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995728,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582244702,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:874",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232000,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293950,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:874",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280368,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582321070,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:881",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305856,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582641518,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:890",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625200,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071592230659,
      "name": "attach_mnt.cold",
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583178797,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:926",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583162384,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071594010705,
      "name": "attach_mnt.cold",
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583753805,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:1037",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737632,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071596051538,
      "name": "attach_mnt.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp, bool beneath)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968576,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:992",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968576,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp, bool beneath)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181040,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:980",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181040,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493541972,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227092900,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287112416,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273206930,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_change_mountpoint"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581964464,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
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
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964464,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902032,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
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
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902032,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955744,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
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
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955744,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```

```json
{
  "name": "attach_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025952,
      "name": "attach_mnt",
      "external": false,
      "loc": "fs/namespace.c:858",
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
        "fs/namespace.c:mnt_change_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025952,
      "name": "attach_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool beneath</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void attach_mnt(struct mount * mnt, struct mount * parent, struct mountpoint * mp)
```
</details>
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

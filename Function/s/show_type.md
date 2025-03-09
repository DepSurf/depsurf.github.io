# Function: <code>show_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581264496,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:85",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc_namespace.c:show_mountinfo"
      ]
    },
    {
      "addr": 18446744071583771191,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:33",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264496,
      "name": "show_type.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071583771191,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581430256,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:85",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071584097112,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:34",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430256,
      "name": "show_type.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071584097112,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581511392,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:85",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071584239781,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:34",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511392,
      "name": "show_type.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071584239781,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581564128,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:87",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071584315776,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:35",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564128,
      "name": "show_type.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071584315776,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581708224,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071584714992,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:35",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708224,
      "name": "show_type.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071584714992,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581875024,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071584942416,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:35",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875024,
      "name": "show_type.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071584942416,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581960144,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071585046400,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:35",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960144,
      "name": "show_type.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071585046400,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582092800,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071585250528,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:32",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092800,
      "name": "show_type.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585250528,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582170176,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071585388416,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:32",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170176,
      "name": "show_type.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585388416,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582407697,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc_namespace.c:show_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586097472,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:32",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586097472,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582460641,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:89",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc_namespace.c:show_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218048,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:32",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218048,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582487697,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:92",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc_namespace.c:show_vfsmnt"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582801905,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:92",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc_namespace.c:show_vfsmnt"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583354416,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:92",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354416,
      "name": "show_type",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583937504,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:92",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937504,
      "name": "show_type",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584151936,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:92",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151936,
      "name": "show_type",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584366176,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:92",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584366176,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493724496,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446603336497661200,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:32",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493724496,
      "name": "show_type.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446603336497661200,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227250444,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227250444,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287331024,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287331024,
      "name": "show_type",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273335046,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273335046,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582138912,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138912,
      "name": "show_type.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582076352,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076352,
      "name": "show_type.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582129392,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071585338816,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:32",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129392,
      "name": "show_type.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585338816,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```

```json
{
  "name": "show_type",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582202448,
      "name": "show_type",
      "external": false,
      "loc": "fs/proc_namespace.c:88",
      "file": "fs/proc_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt"
      ]
    },
    {
      "addr": 18446744071585446144,
      "name": "show_type",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:32",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202448,
      "name": "show_type.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585446144,
      "name": "show_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void show_type(struct seq_file * m, struct super_block * sb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

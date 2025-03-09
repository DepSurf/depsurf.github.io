# Function: <code>proc_pid_get_link</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581631520,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1582",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_map_files_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631520,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719808,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1600",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_map_files_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719808,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581774704,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1617",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774704,
      "name": "proc_pid_get_link.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071581774832,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924000,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1618",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924000,
      "name": "proc_pid_get_link.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071581924128,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582107712,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1584",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107712,
      "name": "proc_pid_get_link.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582107840,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582204016,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1598",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204016,
      "name": "proc_pid_get_link.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582204144,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582369152,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369152,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582369280,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582468896,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468896,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582469024,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582764208,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1723",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764208,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582764416,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582835968,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1737",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835968,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582836176,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582863744,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1736",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582863744,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582863952,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583197888,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1742",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197888,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071583198096,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583698208,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1741",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_map_files_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698208,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584308464,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1742",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_map_files_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308464,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538304,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1742",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_map_files_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538304,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770128,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1738",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_map_files_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770128,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494080112,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494080112,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446603336494080264,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227535500,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227535500,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3227535648,
      "name": "proc_pid_get_link",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287747872,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287747872,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 13835058055287748064,
      "name": "proc_pid_get_link",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273573068,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273573068,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446743936273573172,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582437632,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437632,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582437760,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374800,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374800,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582374928,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582428112,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428112,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582428240,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
```

```json
{
  "name": "proc_pid_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582508512,
      "name": "proc_pid_get_link",
      "external": false,
      "loc": "fs/proc/base.c:1611",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582508512,
      "name": "proc_pid_get_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582508640,
      "name": "proc_pid_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
const char * proc_pid_get_link(struct dentry * dentry, struct inode * inode, struct delayed_call * done)
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

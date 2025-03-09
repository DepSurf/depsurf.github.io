# Function: <code>ns_capable_common</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ns_capable_common(struct user_namespace * ns, int cap, bool audit)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579423264,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423264,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool ns_capable_common(struct user_namespace * ns, int cap, bool audit)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579443664,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:365",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443664,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool ns_capable_common(struct user_namespace * ns, int cap, bool audit)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431808,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:365",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431808,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool ns_capable_common(struct user_namespace * ns, int cap, bool audit)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579460160,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:366",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460160,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool ns_capable_common(struct user_namespace * ns, int cap, bool audit)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:366",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473728,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579475148,
      "name": "ns_capable_common.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508817,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:366",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507408,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071579508817,
      "name": "ns_capable_common.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579527809,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526400,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579527809,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553889,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552480,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579553889,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579584981,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
      ],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584464,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071579585297,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579564917,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
      ],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564480,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071591279092,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579570762,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
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
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579644682,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579740234,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:365",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579871514,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:365",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579920730,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:351",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579959978,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:351",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit",
        "kernel/capability.c:ns_capable_noaudit"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490703408,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490703408,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224768116,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224768116,
      "name": "ns_capable_common",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283528096,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283528096,
      "name": "ns_capable_common",
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271429674,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271429674,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579530193,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528784,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579530193,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579458993,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457584,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579458993,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579527473,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526064,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579527473,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```

```json
{
  "name": "ns_capable_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560578,
      "name": "ns_capable_common",
      "external": false,
      "loc": "kernel/capability.c:364",
      "file": "kernel/capability.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/capability.c:capable",
        "kernel/capability.c:ns_capable_setid",
        "kernel/capability.c:ns_capable_noaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559008,
      "name": "ns_capable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579560578,
      "name": "ns_capable_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
bool ns_capable_common(struct user_namespace * ns, int cap, bool audit)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int opts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool audit</code>
</li>
</ul>
</details>
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
bool ns_capable_common(struct user_namespace * ns, int cap, unsigned int opts)
```
</details>
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

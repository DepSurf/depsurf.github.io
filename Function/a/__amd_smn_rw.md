# Function: <code>__amd_smn_rw</code>

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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262624,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:92",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262624,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259440,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:92",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259440,
      "name": "__amd_smn_rw",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276240,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:96",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276240,
      "name": "__amd_smn_rw",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:102",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287584,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579289770,
      "name": "__amd_smn_rw.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:122",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311536,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579313978,
      "name": "__amd_smn_rw.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:123",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326704,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579329093,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:129",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330752,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579333141,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:132",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360096,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071579362629,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:132",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359296,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071591264142,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:132",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363696,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071591206464,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:145",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424256,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071592079222,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:145",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492768,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071593845712,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587664,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:158",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587664,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600160,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:166",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600160,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629920,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:182",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629920,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:129",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326656,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579329045,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:129",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261104,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579263461,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:129",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326576,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579328965,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```

```json
{
  "name": "__amd_smn_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__amd_smn_rw",
      "external": false,
      "loc": "arch/x86/kernel/amd_nb.c:129",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:amd_smn_write",
        "arch/x86/kernel/amd_nb.c:amd_smn_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334864,
      "name": "__amd_smn_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579337253,
      "name": "__amd_smn_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __amd_smn_rw(u16 node, u32 address, u32 * value, bool write)
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

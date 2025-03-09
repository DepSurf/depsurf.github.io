# Function: <code>gdb_cmd_query</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580094556,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:697",
      "file": "kernel/debug/gdbstub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
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
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580128183,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:697",
      "file": "kernel/debug/gdbstub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580168519,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:697",
      "file": "kernel/debug/gdbstub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
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
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580175099,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
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
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580227479,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
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
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580288388,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
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
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580341672,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580392640,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    },
    {
      "addr": 18446744071580396963,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441424,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    },
    {
      "addr": 18446744071580445747,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580524416,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
    },
    {
      "addr": 18446744071580528883,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512480,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1145
    },
    {
      "addr": 18446744071591316681,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515888,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1158
    },
    {
      "addr": 18446744071591258941,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:695",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687312,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071592164211,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:695",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898000,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1227
    },
    {
      "addr": 18446744071593937437,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189232,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:695",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189232,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283456,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:695",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283456,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389552,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:695",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389552,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491711184,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491711184,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225663760,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225663760,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284734384,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284734384,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
    }
  ]
}
```
</details>
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410224,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    },
    {
      "addr": 18446744071580414547,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357312,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    },
    {
      "addr": 18446744071580361635,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401472,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    },
    {
      "addr": 18446744071580405795,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
```

```json
{
  "name": "gdb_cmd_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gdb_cmd_query",
      "external": false,
      "loc": "kernel/debug/gdbstub.c:698",
      "file": "kernel/debug/gdbstub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457056,
      "name": "gdb_cmd_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    },
    {
      "addr": 18446744071580461379,
      "name": "gdb_cmd_query.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gdb_cmd_query(struct kgdb_state * ks)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void gdb_cmd_query(struct kgdb_state * ks)
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

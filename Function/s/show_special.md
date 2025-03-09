# Function: <code>show_special</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580049917,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1171",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
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
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580083943,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1170",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
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
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580124199,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1175",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
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
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580129644,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1176",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
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
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580182181,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1176",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
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
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580242109,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1183",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
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
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580294164,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1139",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580347696,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347696,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580396464,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396464,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580473360,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1193",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473360,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580461488,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1211",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461488,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
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
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580465888,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1210",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580465888,
      "name": "show_special.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580632848,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1216",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632848,
      "name": "show_special.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580839152,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1386",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839152,
      "name": "show_special.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581126224,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1364",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126224,
      "name": "show_special.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581225920,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1361",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225920,
      "name": "show_special.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1721
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581332256,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1362",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332256,
      "name": "show_special.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1754
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491665664,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491665664,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225615844,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225615844,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284669936,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284669936,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272057376,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272057376,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365264,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365264,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312432,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312432,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356512,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356512,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
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
void show_special(struct audit_context * context, int * call_panic)
```

```json
{
  "name": "show_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411824,
      "name": "show_special",
      "external": false,
      "loc": "kernel/auditsc.c:1188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411824,
      "name": "show_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
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
void show_special(struct audit_context * context, int * call_panic)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void show_special(struct audit_context * context, int * call_panic)
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

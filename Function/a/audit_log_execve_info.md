# Function: <code>audit_log_execve_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580050525,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1137",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080912,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:996",
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
      "addr": 18446744071580080912,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121152,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1001",
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
      "addr": 18446744071580121152,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126944,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1002",
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
      "addr": 18446744071580126944,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1451
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179408,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1002",
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
      "addr": 18446744071580179408,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1451
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239296,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1009",
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
      "addr": 18446744071580239296,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1437
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292176,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:965",
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
      "addr": 18446744071580292176,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1438
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343056,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343056,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391824,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391824,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470512,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:992",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470512,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580458688,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1010",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580458688,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580462768,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1009",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462768,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629648,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1015",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629648,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1615
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1138",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835696,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1663
    },
    {
      "addr": 18446744071593935751,
      "name": "audit_log_execve_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123616,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1116",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123616,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1679
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215456,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1117",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215456,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1685
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321824,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:1118",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321824,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1732
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491658296,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491658296,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1188
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225612220,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225612220,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284661056,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284661056,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1468
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272051260,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272051260,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 922
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360624,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360624,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307792,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307792,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351872,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351872,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
```

```json
{
  "name": "audit_log_execve_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407168,
      "name": "audit_log_execve_info",
      "external": false,
      "loc": "kernel/auditsc.c:987",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407168,
      "name": "audit_log_execve_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
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
void audit_log_execve_info(struct audit_context * context, struct audit_buffer * * ab)
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

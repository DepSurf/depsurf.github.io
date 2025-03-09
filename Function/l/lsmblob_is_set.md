# Function: <code>lsmblob_is_set</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580455533,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:207",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071580481536,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:207",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_lsm"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443888,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580444144,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:209",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071580469904,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:209",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_lsm"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431824,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580448161,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:210",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071580473292,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:210",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_lsm"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436224,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580613121,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:210",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071580640444,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:210",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_lsm"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600848,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580809046,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:194",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071580847033,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:194",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_pid_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804464,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581094982,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:214",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071581133897,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:214",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_pid_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090032,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581186582,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:214",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071581223737,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:214",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_pid_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181648,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```

```json
{
  "name": "lsmblob_is_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292751,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:292",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    },
    {
      "addr": 18446744071581330034,
      "name": "lsmblob_is_set",
      "external": false,
      "loc": "include/linux/security.h:292",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_pid_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287328,
      "name": "lsmblob_is_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool lsmblob_is_set(struct lsmblob * blob)
```
</details>
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

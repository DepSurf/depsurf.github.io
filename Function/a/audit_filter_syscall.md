# Function: <code>audit_filter_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
enum audit_state audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056320,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:748",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_syscall_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056320,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
enum audit_state audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089568,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:753",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089568,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
enum audit_state audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129872,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:758",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129872,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
enum audit_state audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580135664,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:759",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135664,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
enum audit_state audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580188112,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:759",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188112,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247888,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:766",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247888,
      "name": "audit_filter_syscall.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302496,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:760",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302496,
      "name": "audit_filter_syscall.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580354768,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354768,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580403536,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403536,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580478928,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:792",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478928,
      "name": "audit_filter_syscall.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580466672,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:808",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466672,
      "name": "audit_filter_syscall.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580470432,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:808",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470432,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580637496,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:814",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637440,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071592162731,
      "name": "audit_filter_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:848",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848960,
      "name": "audit_filter_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071593935891,
      "name": "audit_filter_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581139188,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:871",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free"
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
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581232100,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:872",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free"
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
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581338260,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:869",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491668896,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491668896,
      "name": "audit_filter_syscall.constprop.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225623204,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225623204,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284674224,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284674224,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272060348,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272060348,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372336,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580372336,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580319504,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319504,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580363584,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363584,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580418928,
      "name": "audit_filter_syscall",
      "external": false,
      "loc": "kernel/auditsc.c:780",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418928,
      "name": "audit_filter_syscall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
enum audit_state audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void audit_filter_syscall(struct task_struct * tsk, struct audit_context * ctx)
```
</details>
</li>
</ul>

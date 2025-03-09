# Function: <code>audit_filter_inodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057760,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:805",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057760,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090960,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:810",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090960,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131264,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:815",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131264,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580136976,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:816",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136976,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580189552,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:816",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189552,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580249408,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:823",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249408,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302736,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:817",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302736,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580354992,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354992,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580403760,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403760,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580484449,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:843",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478464,
      "name": "audit_filter_inodes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071580480768,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580472802,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:859",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467104,
      "name": "audit_filter_inodes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071580469104,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580472256,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:858",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472256,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580639401,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:864",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162827,
      "name": "audit_filter_inodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580639344,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580852119,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:898",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846528,
      "name": "audit_filter_inodes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071593935823,
      "name": "audit_filter_inodes.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580850256,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581136928,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:901",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136928,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581229840,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:902",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229840,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581335968,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:900",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335968,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491669168,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491669168,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225623436,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225623436,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284676768,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284676768,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272060546,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272060546,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372560,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580372560,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580319728,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319728,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580363808,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363808,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void audit_filter_inodes(struct task_struct * tsk, struct audit_context * ctx)
```

```json
{
  "name": "audit_filter_inodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580419168,
      "name": "audit_filter_inodes",
      "external": true,
      "loc": "kernel/auditsc.c:831",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419168,
      "name": "audit_filter_inodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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

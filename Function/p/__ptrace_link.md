# Function: <code>__ptrace_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413552,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:37",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413552,
      "name": "__ptrace_link.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579416496,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579425909,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:37",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425824,
      "name": "__ptrace_link.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579428784,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579448368,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:66",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448368,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579436320,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:63",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436320,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579464592,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:63",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464592,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579478112,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:63",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478112,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579511440,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:63",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511440,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531056,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531056,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557200,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557200,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579588656,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588656,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568672,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568672,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579574208,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:68",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574208,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579647197,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:68",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650432,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743343,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:68",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745408,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579874047,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:68",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876736,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579923903,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:69",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926048,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579963151,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:69",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965376,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490712544,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490712544,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224772144,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224772144,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283536288,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283536288,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271432152,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_link"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271432106,
      "name": "__ptrace_link.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446743936271433254,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533504,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533504,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579462272,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462272,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579530784,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530784,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __ptrace_link(struct task_struct * child, struct task_struct * new_parent, const struct cred * ptracer_cred)
```

```json
{
  "name": "__ptrace_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579563856,
      "name": "__ptrace_link",
      "external": true,
      "loc": "kernel/ptrace.c:67",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563856,
      "name": "__ptrace_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * ptracer_cred</code>
</li>
</ul>
</details>
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

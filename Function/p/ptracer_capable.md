# Function: <code>ptracer_capable</code>

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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445120,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:498",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445120,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433152,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:498",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433152,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461504,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:499",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461504,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475104,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:499",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475104,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508768,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:501",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508768,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527760,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527760,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553840,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553840,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585248,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585248,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565312,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565312,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570832,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:522",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570832,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644752,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:522",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644752,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740320,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:523",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740320,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871616,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:523",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871616,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920832,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:511",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920832,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960080,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:511",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960080,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490707080,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490707080,
      "name": "ptracer_capable",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224769904,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224769904,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283530880,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283530880,
      "name": "ptracer_capable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271431142,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271431142,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530144,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530144,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458944,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458944,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527424,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527424,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
```

```json
{
  "name": "ptracer_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560496,
      "name": "ptracer_capable",
      "external": true,
      "loc": "kernel/capability.c:518",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "security/commoncap.c:cap_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560496,
      "name": "ptracer_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool ptracer_capable(struct task_struct * tsk, struct user_namespace * ns)
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

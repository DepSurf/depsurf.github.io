# Function: <code>ptrace_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413968,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:316",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:SyS_ptrace",
        "kernel/ptrace.c:compat_SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413968,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426240,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:315",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426240,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448592,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:328",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448592,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436544,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:343",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436544,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464816,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:343",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464816,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579478336,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:343",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478336,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511664,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:343",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511664,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531312,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:358",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531312,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557456,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557456,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588912,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588912,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568928,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:357",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568928,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574464,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:374",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574464,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647696,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:374",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x64_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647696,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743440,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:388",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743440,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874704,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:388",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874704,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924016,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:389",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924016,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579963280,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:406",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963280,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490712920,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__arm64_compat_sys_ptrace",
        "kernel/ptrace.c:__arm64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490712920,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224773856,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283536672,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_compat_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283536672,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271434666,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533760,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533760,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462528,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462528,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531040,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531040,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "ptrace_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564096,
      "name": "ptrace_attach",
      "external": false,
      "loc": "kernel/ptrace.c:363",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564096,
      "name": "ptrace_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ptrace_attach(struct task_struct * task, long int request, long unsigned int addr, long unsigned int flags)
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

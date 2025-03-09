# Function: <code>x86_fsbase_read_task</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579030864,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:341",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030864,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038512,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:332",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038512,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579040912,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:332",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040912,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052698,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:330",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051312,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054528,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:436",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054528,
      "name": "x86_fsbase_read_task",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061360,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:436",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061360,
      "name": "x86_fsbase_read_task",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082640,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:460",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082640,
      "name": "x86_fsbase_read_task",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111248,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:460",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111248,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579149904,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:460",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149904,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152016,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:461",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152016,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181312,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:461",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/ptrace.c:getreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181312,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041264,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:332",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041264,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578974224,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:332",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578974224,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579040848,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:332",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040848,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```

```json
{
  "name": "x86_fsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579044512,
      "name": "x86_fsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:332",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044512,
      "name": "x86_fsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```
</details>
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
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct * task)
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

# Function: <code>x86_gsbase_write_task</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579031072,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:376",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579031072,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579040221,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:367",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038720,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579042621,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:367",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041120,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579053126,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:365",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051520,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579056402,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:473",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:putreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054752,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579063159,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:473",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:putreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061664,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579084375,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:497",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:putreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082944,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579113222,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:497",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:putreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111696,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579151974,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:497",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:putreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579150400,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579154292,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:498",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:putreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152512,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183720,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:498",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:putreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181808,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579042973,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:367",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041472,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976022,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:367",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578974496,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579042557,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:367",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041056,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579046264,
      "name": "x86_gsbase_write_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:367",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044720,
      "name": "x86_gsbase_write_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
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
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void x86_gsbase_write_task(struct task_struct * task, long unsigned int gsbase)
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

# Function: <code>x86_fsgsbase_read_task</code>

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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030240,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:298",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030240,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579037696,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:289",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037696,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579040096,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:289",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040096,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050288,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:287",
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
      "addr": 18446744071579050288,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054128,
      "name": "x86_fsgsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:363",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/ptrace.c:putreg32",
        "arch/x86/kernel/ptrace.c:putreg32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054128,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579060928,
      "name": "x86_fsgsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:363",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/ptrace.c:putreg32",
        "arch/x86/kernel/ptrace.c:putreg32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060928,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082176,
      "name": "x86_fsgsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:387",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/ptrace.c:putreg32",
        "arch/x86/kernel/ptrace.c:putreg32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082176,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579110768,
      "name": "x86_fsgsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:387",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/ptrace.c:putreg32",
        "arch/x86/kernel/ptrace.c:putreg32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579110768,
      "name": "x86_fsgsbase_read_task",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579149376,
      "name": "x86_fsgsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:387",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/ptrace.c:putreg32",
        "arch/x86/kernel/ptrace.c:putreg32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149376,
      "name": "x86_fsgsbase_read_task",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151488,
      "name": "x86_fsgsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:388",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/ptrace.c:putreg32",
        "arch/x86/kernel/ptrace.c:putreg32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151488,
      "name": "x86_fsgsbase_read_task",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180784,
      "name": "x86_fsgsbase_read_task",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:388",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/ptrace.c:putreg32",
        "arch/x86/kernel/ptrace.c:putreg32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180784,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579040448,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:289",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040448,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578973408,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:289",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973408,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579040032,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:289",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040032,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```

```json
{
  "name": "x86_fsgsbase_read_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579043696,
      "name": "x86_fsgsbase_read_task",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:289",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043696,
      "name": "x86_fsgsbase_read_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
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
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct * task, short unsigned int selector)
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

# Function: <code>__save_stack_trace</code>

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
void __save_stack_trace(struct stack_trace * trace, struct task_struct * task, struct pt_regs * regs, bool nosched)
```

```json
{
  "name": "__save_stack_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098208,
      "name": "__save_stack_trace",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:31",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_regs",
        "arch/x86/kernel/stacktrace.c:save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098208,
      "name": "__save_stack_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void __save_stack_trace(struct stack_trace * trace, struct task_struct * task, struct pt_regs * regs, bool nosched)
```

```json
{
  "name": "__save_stack_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090160,
      "name": "__save_stack_trace",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:33",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_regs",
        "arch/x86/kernel/stacktrace.c:save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090160,
      "name": "__save_stack_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void __save_stack_trace(struct stack_trace * trace, struct task_struct * task, struct pt_regs * regs, bool nosched)
```

```json
{
  "name": "__save_stack_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100944,
      "name": "__save_stack_trace",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:33",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_regs",
        "arch/x86/kernel/stacktrace.c:save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100944,
      "name": "__save_stack_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void __save_stack_trace(struct stack_trace * trace, struct task_struct * task, struct pt_regs * regs, bool nosched)
```

```json
{
  "name": "__save_stack_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106512,
      "name": "__save_stack_trace",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:33",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_regs",
        "arch/x86/kernel/stacktrace.c:save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106512,
      "name": "__save_stack_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void __save_stack_trace(struct stack_trace * trace, struct task_struct * task, struct pt_regs * regs, bool nosched)
```

```json
{
  "name": "__save_stack_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112176,
      "name": "__save_stack_trace",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:33",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_regs",
        "arch/x86/kernel/stacktrace.c:save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112176,
      "name": "__save_stack_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __save_stack_trace(struct task_struct * tsk, struct stack_trace * trace, unsigned int nosched)
```

```json
{
  "name": "__save_stack_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490236832,
      "name": "__save_stack_trace",
      "external": false,
      "loc": "arch/arm64/kernel/stacktrace.c:171",
      "file": "arch/arm64/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/stacktrace.c:save_stack_trace",
        "arch/arm64/kernel/stacktrace.c:save_stack_trace_tsk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490236832,
      "name": "__save_stack_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void __save_stack_trace(struct task_struct * tsk, struct stack_trace * trace, unsigned int nosched)
```

```json
{
  "name": "__save_stack_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224432308,
      "name": "__save_stack_trace",
      "external": false,
      "loc": "arch/arm/kernel/stacktrace.c:102",
      "file": "arch/arm/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/stacktrace.c:save_stack_trace",
        "arch/arm/kernel/stacktrace.c:save_stack_trace_tsk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224432308,
      "name": "__save_stack_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __save_stack_trace(struct stack_trace * trace, struct task_struct * task, struct pt_regs * regs, bool nosched)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void __save_stack_trace(struct stack_trace * trace, struct task_struct * task, struct pt_regs * regs, bool nosched)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __save_stack_trace(struct task_struct * tsk, struct stack_trace * trace, unsigned int nosched)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __save_stack_trace(struct task_struct * tsk, struct stack_trace * trace, unsigned int nosched)
```
</details>
</li>
</ul>

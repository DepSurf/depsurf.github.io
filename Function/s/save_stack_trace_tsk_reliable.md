# Function: <code>save_stack_trace_tsk_reliable</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```

```json
{
  "name": "save_stack_trace_tsk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871648,
      "name": "save_stack_trace_tsk_reliable",
      "external": true,
      "loc": "kernel/stacktrace.c:74",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871648,
      "name": "save_stack_trace_tsk_reliable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 52
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
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```

```json
{
  "name": "save_stack_trace_tsk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579101424,
      "name": "save_stack_trace_tsk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:162",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101424,
      "name": "save_stack_trace_tsk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```

```json
{
  "name": "save_stack_trace_tsk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106992,
      "name": "save_stack_trace_tsk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:162",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106992,
      "name": "save_stack_trace_tsk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```

```json
{
  "name": "save_stack_trace_tsk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112672,
      "name": "save_stack_trace_tsk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:148",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112672,
      "name": "save_stack_trace_tsk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```

```json
{
  "name": "save_stack_trace_tsk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282595568,
      "name": "save_stack_trace_tsk_reliable",
      "external": true,
      "loc": "arch/powerpc/kernel/stacktrace.c:205",
      "file": "arch/powerpc/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282595568,
      "name": "save_stack_trace_tsk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct * tsk, struct stack_trace * trace)
```
</details>
</li>
</ul>

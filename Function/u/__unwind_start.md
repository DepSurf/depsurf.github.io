# Function: <code>__unwind_start</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579278800,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:279",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278800,
      "name": "__unwind_start",
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275616,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:359",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275616,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294176,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:384",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294176,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305936,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:384",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305936,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579330480,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:388",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330480,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345744,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:366",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345744,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350080,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:366",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350080,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379824,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:363",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379824,
      "name": "__unwind_start",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378464,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:363",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378464,
      "name": "__unwind_start",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382080,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:363",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382080,
      "name": "__unwind_start",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443776,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:363",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443776,
      "name": "__unwind_start",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514048,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:362",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514048,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613408,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:373",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613408,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626016,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:373",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626016,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655072,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:373",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655072,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345984,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:366",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345984,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579278192,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:366",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278192,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345904,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:366",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345904,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```

```json
{
  "name": "__unwind_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354352,
      "name": "__unwind_start",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:366",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354352,
      "name": "__unwind_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __unwind_start(struct unwind_state * state, struct task_struct * task, struct pt_regs * regs, long unsigned int * first_frame)
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

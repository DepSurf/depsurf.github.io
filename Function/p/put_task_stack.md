# Function: <code>put_task_stack</code>

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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387872,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:336",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "kernel/sched/core.c:sched_show_task",
        "kernel/sched/core.c:finish_task_switch",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387872,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579375360,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:360",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/sched/core.c:finish_task_switch",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375360,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402208,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:366",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "kernel/sched/core.c:finish_task_switch",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402208,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417904,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:392",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "kernel/sched/core.c:finish_task_switch",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417904,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448752,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:435",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk",
        "kernel/sched/core.c:finish_task_switch",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448752,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:441",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478965,
      "name": "put_task_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579466960,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493264,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493264,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523456,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:455",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523456,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505008,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:441",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505008,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508448,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:445",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "kernel/bpf/stackmap.c:bpf_get_task_stack",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508448,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577536,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:445",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "kernel/bpf/stackmap.c:bpf_get_task_stack",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577536,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668512,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:__get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "kernel/bpf/stackmap.c:bpf_get_task_stack",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668512,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788528,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:534",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:__get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "kernel/bpf/stackmap.c:bpf_get_task_stack",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788528,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836000,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:598",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:__get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "kernel/bpf/stackmap.c:bpf_get_task_stack",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836000,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876032,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:578",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:__get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "kernel/bpf/stackmap.c:bpf_get_task_stack",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876032,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490626872,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:get_wchan",
        "arch/arm64/kernel/stacktrace.c:__save_stack_trace",
        "arch/arm64/kernel/traps.c:dump_backtrace",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "fs/proc/array.c:do_task_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490626872,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
  "name": "put_task_stack",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "put_task_stack",
      "external": false,
      "loc": "include/linux/sched/task_stack.h:75",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_task_stack",
      "external": false,
      "loc": "include/linux/sched/task_stack.h:75",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227561480,
      "name": "put_task_stack",
      "external": false,
      "loc": "include/linux/sched/task_stack.h:75",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_task_stack",
      "external": false,
      "loc": "include/linux/sched/task_stack.h:75",
      "file": "lib/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283444896,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/process.c:show_stack",
        "arch/powerpc/kernel/process.c:get_wchan",
        "arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "fs/proc/array.c:do_task_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283444896,
      "name": "put_task_stack",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271384850,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": [
        "kernel/sched/core.c:finish_task_switch",
        "fs/proc/array.c:do_task_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271383338,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579466928,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466928,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395872,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395872,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579466848,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466848,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void put_task_stack(struct task_struct * tsk)
```

```json
{
  "name": "put_task_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498592,
      "name": "put_task_stack",
      "external": true,
      "loc": "kernel/fork.c:450",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:get_wchan",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable",
        "kernel/stacktrace.c:stack_trace_save_tsk",
        "fs/proc/array.c:do_task_stat",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall",
        "lib/syscall.c:collect_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498592,
      "name": "put_task_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void put_task_stack(struct task_struct * tsk)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void put_task_stack(struct task_struct * tsk)
```
</details>
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

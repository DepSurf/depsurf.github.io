# Function: <code>stack_trace_save_tsk</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049152,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:137",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049152,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098240,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:137",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098240,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160752,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:137",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160752,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145040,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:135",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145040,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149728,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:135",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149728,
      "name": "stack_trace_save_tsk",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294256,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:135",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294256,
      "name": "stack_trace_save_tsk",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502896,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:136",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502896,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756048,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:136",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756048,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838720,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:136",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838720,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928000,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:136",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/latencytop.c:__account_scheduler_latency",
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928000,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int stack_trace_save_tsk(struct task_struct * task, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491309592,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:295",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491309592,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
unsigned int stack_trace_save_tsk(struct task_struct * task, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225306172,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:295",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225306172,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
unsigned int stack_trace_save_tsk(struct task_struct * task, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284235424,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:295",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284235424,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
unsigned int stack_trace_save_tsk(struct task_struct * task, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271818680,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:295",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271818680,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067440,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:137",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067440,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012256,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:137",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012256,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058512,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:137",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058512,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save_tsk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109344,
      "name": "stack_trace_save_tsk",
      "external": true,
      "loc": "kernel/stacktrace.c:137",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/latencytop.c:__account_scheduler_latency",
        "fs/proc/base.c:proc_pid_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109344,
      "name": "stack_trace_save_tsk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct * tsk, long unsigned int * store, unsigned int size, unsigned int skipnr)
```
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
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

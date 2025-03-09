# Function: <code>ftrace_graph_ret_addr</code>

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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580348656,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/trace_functions_graph.c:302",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:unwind_get_return_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580348656,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361440,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/trace_functions_graph.c:302",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361440,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580415104,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/trace_functions_graph.c:303",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415104,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476800,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/trace_functions_graph.c:303",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476800,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580550784,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550784,
      "name": "ftrace_graph_ret_addr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607712,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607712,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654704,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654704,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756992,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:296",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756992,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745072,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:296",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745072,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749568,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:296",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749568,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932992,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:296",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932992,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172944,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:307",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172944,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487904,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:307",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487904,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605840,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:332",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605840,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718272,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:332",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718272,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491959264,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:292",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491959264,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225894836,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:292",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225894836,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285065456,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/process.c:show_stack",
        "arch/powerpc/kernel/process.c:show_stack",
        "arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285065456,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272233206,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/stacktrace.c:walk_stackframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272233206,
      "name": "ftrace_graph_ret_addr",
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623504,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623504,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569760,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569760,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614752,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614752,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
```

```json
{
  "name": "ftrace_graph_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672208,
      "name": "ftrace_graph_ret_addr",
      "external": true,
      "loc": "kernel/trace/fgraph.c:273",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672208,
      "name": "ftrace_graph_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int ftrace_graph_ret_addr(struct task_struct * task, int * idx, long unsigned int ret, long unsigned int * retp)
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

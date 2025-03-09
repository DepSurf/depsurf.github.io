# Function: <code>trace_buffer_lock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215936,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:1670",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_current_buffer_lock_reserve",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215936,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251984,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:1926",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251984,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297840,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:1960",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297840,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311392,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2137",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311392,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364528,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364528,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425936,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2152",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425936,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580481680,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2153",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481680,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537536,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2337",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537536,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580585072,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585072,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684112,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2467",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684112,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674944,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2611",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674944,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580677200,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2620",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580677200,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851424,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2644",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851424,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581080224,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2637",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080224,
      "name": "trace_buffer_lock_reserve",
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387264,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2661",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387264,
      "name": "trace_buffer_lock_reserve",
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481872,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2732",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481872,
      "name": "trace_buffer_lock_reserve",
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct trace_buffer * buffer, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592752,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2727",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592752,
      "name": "trace_buffer_lock_reserve",
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491882832,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491882832,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225824628,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225824628,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284961328,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284961328,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272172960,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272172960,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553872,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553872,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500576,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500576,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545120,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545120,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ring_buffer_event * trace_buffer_lock_reserve(struct ring_buffer * buffer, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580601696,
      "name": "trace_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2363",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601696,
      "name": "trace_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer * buffer</code> ➡️ <code>struct trace_buffer * buffer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int trace_ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int pc</code>
</li>
</ul>
</details>
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

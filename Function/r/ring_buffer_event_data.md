# Function: <code>ring_buffer_event_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184784,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:265",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
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
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184784,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219616,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:265",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219616,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580260560,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:265",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260560,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580272336,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:266",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272336,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580325504,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:265",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_process_export",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325504,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580386800,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:271",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_process_export",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580386800,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580441264,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:272",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441264,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580495344,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:263",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495344,
      "name": "ring_buffer_event_data",
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580543600,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543600,
      "name": "ring_buffer_event_data",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633904,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633904,
      "name": "ring_buffer_event_data",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623840,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:274",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:ftrace_exports",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623840,
      "name": "ring_buffer_event_data",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626656,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:274",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:ftrace_exports",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626656,
      "name": "ring_buffer_event_data",
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798480,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:274",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:ftrace_exports",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798480,
      "name": "ring_buffer_event_data",
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020976,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:282",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_puts",
        "kernel/trace/trace.c:__trace_puts",
        "kernel/trace/trace.c:ftrace_exports",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020976,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322160,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:282",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_puts",
        "kernel/trace/trace.c:__trace_puts",
        "kernel/trace/trace.c:ftrace_exports",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322160,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416192,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:282",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_array_puts",
        "kernel/trace/trace.c:__trace_array_puts",
        "kernel/trace/trace.c:ftrace_exports",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func",
        "kernel/trace/trace_fprobe.c:fexit_trace_func",
        "kernel/trace/trace_fprobe.c:fentry_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416192,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524224,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:283",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_array_puts",
        "kernel/trace/trace.c:__trace_array_puts",
        "kernel/trace/trace.c:ftrace_exports",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func",
        "kernel/trace/trace_fprobe.c:fexit_trace_func",
        "kernel/trace/trace_fprobe.c:fentry_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524224,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491823984,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491823984,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225775212,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225775212,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284889200,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284889200,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272134810,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272134810,
      "name": "ring_buffer_event_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580512400,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512400,
      "name": "ring_buffer_event_data",
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580459888,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459888,
      "name": "ring_buffer_event_data",
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503648,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503648,
      "name": "ring_buffer_event_data",
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
void * ring_buffer_event_data(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580559984,
      "name": "ring_buffer_event_data",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:264",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:peek_next_entry",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559984,
      "name": "ring_buffer_event_data",
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

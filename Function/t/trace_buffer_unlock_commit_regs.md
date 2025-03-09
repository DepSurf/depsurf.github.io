# Function: <code>trace_buffer_unlock_commit_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220304,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:1746",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220304,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257136,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2109",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257136,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580299648,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2197",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580299648,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313120,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313120,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580366256,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2386",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366256,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580427664,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2398",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427664,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483312,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2399",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483312,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538256,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2583",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538256,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580585824,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585824,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684864,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2720",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684864,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675696,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2866",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675696,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, unsigned int trace_ctx, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580677952,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2888",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580677952,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, unsigned int trace_ctx, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852368,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2948",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852368,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, unsigned int trace_ctx, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081344,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2946",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081344,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, unsigned int trace_ctx, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388464,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2970",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388464,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, unsigned int trace_ctx, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483072,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:3041",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483072,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct trace_buffer * buffer, struct ring_buffer_event * event, unsigned int trace_ctx, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593920,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:3035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593920,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491883760,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491883760,
      "name": "trace_buffer_unlock_commit_regs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225825820,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
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
      "addr": 3225825820,
      "name": "trace_buffer_unlock_commit_regs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284962672,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace",
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
      "addr": 13835058055284962672,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272173876,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272173876,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580554624,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554624,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580501328,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501328,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545872,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545872,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void trace_buffer_unlock_commit_regs(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc, struct pt_regs * regs)
```

```json
{
  "name": "trace_buffer_unlock_commit_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602544,
      "name": "trace_buffer_unlock_commit_regs",
      "external": true,
      "loc": "kernel/trace/trace.c:2609",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602544,
      "name": "trace_buffer_unlock_commit_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
<li>
<b>Param reordered. </b>
<code>tr, buffer, event, flags, pc, regs</code> ➡️ <code>tr, buffer, event, trace_ctx, regs</code>
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

# Function: <code>trace_buffer_unlock_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void trace_buffer_unlock_commit(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220192,
      "name": "trace_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/trace.c:1695",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/trace_events.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220192,
      "name": "trace_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580294484,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1109",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580300982,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1109",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314257,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1109",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580329178,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1109",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580338133,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1109",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406338,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1109",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580300113,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1128",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580338350,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1128",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580346854,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1128",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580361530,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1128",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383904,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1128",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454482,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1128",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580313385,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1244",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351582,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1244",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580359682,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1244",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374797,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1244",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580395334,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1244",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465817,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1244",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580366521,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1246",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405177,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1246",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580413330,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1246",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580429371,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1246",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450737,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1246",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580521785,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1246",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580427911,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1251",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580466811,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1251",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580475030,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1251",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491201,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1251",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512608,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1251",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609702,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1251",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580483559,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1314",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580522649,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1314",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580530717,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1314",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580546545,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1314",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570288,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1314",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580668454,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1314",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580538760,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1360",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580579038,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1360",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586964,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1360",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580603160,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1360",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580628016,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1360",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732038,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1360",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580586328,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580626126,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634116,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580650344,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580674592,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580782629,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580724376,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1447",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580734480,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1447",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580751456,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1447",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580779088,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1447",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896558,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1447",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580713848,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1303",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723456,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1303",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580740192,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1303",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766992,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1303",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890814,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1303",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580719967,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1307",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580728815,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1307",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745846,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1307",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580772735,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1307",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894773,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1307",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580898901,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1313",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910550,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1313",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928846,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1313",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956703,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1313",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096341,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1313",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581134554,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1321",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147367,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1321",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166231,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1321",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581445884,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1321",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460279,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1321",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480819,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1321",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581542940,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1352",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577655,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1352",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598751,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1352",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581655301,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1370",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689959,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1370",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711183,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1370",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491884040,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491927984,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491954860,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491982848,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492099176,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225826116,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 3225864672,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 3225889852,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note"
      ],
      "caller_func": []
    },
    {
      "addr": 3225916996,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225993488,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284963128,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285027032,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285059472,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285102916,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285293440,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272174192,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272208576,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272228728,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272251418,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580555128,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580594926,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602916,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580619144,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580643392,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751429,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580501832,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542455,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549300,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580565797,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589609,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697621,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580546376,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586174,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580594164,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610392,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634640,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580742677,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_buffer_unlock_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580603080,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580643070,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580651108,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_mmiotrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667484,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692144,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800693,
      "name": "trace_buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.h:1380",
      "file": "kernel/trace/trace_uprobe.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void trace_buffer_unlock_commit(struct trace_array * tr, struct ring_buffer * buffer, struct ring_buffer_event * event, long unsigned int flags, int pc)
```
</details>
</li>
</ul>

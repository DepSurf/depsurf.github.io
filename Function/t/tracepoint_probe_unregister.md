# Function: <code>tracepoint_probe_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153648,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:311",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_graph",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153648,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188064,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:311",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_graph",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188064,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580228672,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:315",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_graph",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228672,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238512,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:316",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_graph",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238512,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289728,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:316",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_graph",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289728,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351664,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:314",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_graph",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351664,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407104,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:360",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407104,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580460768,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460768,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580509680,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509680,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595280,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer",
        "kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer",
        "kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595280,
      "name": "tracepoint_probe_unregister",
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580586864,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:422",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer",
        "kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer",
        "kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586864,
      "name": "tracepoint_probe_unregister",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587648,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:543",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587648,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:543",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592165408,
      "name": "tracepoint_probe_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580758640,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:543",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593938794,
      "name": "tracepoint_probe_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580974288,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:543",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596001905,
      "name": "tracepoint_probe_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581271872,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:543",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_events_user.c:user_event_reg",
        "kernel/trace/trace_events_user.c:user_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596520466,
      "name": "tracepoint_probe_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581367024,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:543",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_unregister",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "arch/x86/kernel/trace.c:osnoise_arch_register",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/trace_osnoise.c:osnoise_hook_events",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_events_user.c:user_event_reg",
        "kernel/trace/trace_events_user.c:user_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597420831,
      "name": "tracepoint_probe_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581471904,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491787832,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491787832,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225735568,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_exit_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/trace_syscalls.c:syscall_enter_register",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225735568,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284838144,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284838144,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272102360,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272102360,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478480,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478480,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425616,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425616,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469728,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469728,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int tracepoint_probe_unregister(struct tracepoint * tp, void * probe, void * data)
```

```json
{
  "name": "tracepoint_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525424,
      "name": "tracepoint_probe_unregister",
      "external": true,
      "loc": "kernel/tracepoint.c:347",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/ftrace.c:ftrace_pid_follow_fork",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_start_sched_switch",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_switch.c:tracing_sched_unregister",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/fgraph.c:unregister_ftrace_graph",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_follow_fork",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/trace_events.c:trace_event_reg",
        "kernel/trace/bpf_trace.c:bpf_probe_unregister",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525424,
      "name": "tracepoint_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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

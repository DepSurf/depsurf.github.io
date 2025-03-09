# Function: <code>tracing_gen_ctx_irq_test</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status)
```

```json
{
  "name": "tracing_gen_ctx_irq_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580673040,
      "name": "tracing_gen_ctx_irq_test",
      "external": true,
      "loc": "kernel/trace/trace.c:2598",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_trace_call",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update",
        "kernel/trace/trace_events_inject.c:parse_entry",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673040,
      "name": "tracing_gen_ctx_irq_test",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status)
```

```json
{
  "name": "tracing_gen_ctx_irq_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847216,
      "name": "tracing_gen_ctx_irq_test",
      "external": true,
      "loc": "kernel/trace/trace.c:2621",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_trace_call",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update",
        "kernel/trace/trace_events_trigger.c:stacktrace_trigger",
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func",
        "kernel/trace/trace_events_inject.c:parse_entry",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847216,
      "name": "tracing_gen_ctx_irq_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status)
```

```json
{
  "name": "tracing_gen_ctx_irq_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581075760,
      "name": "tracing_gen_ctx_irq_test",
      "external": true,
      "loc": "kernel/trace/trace.c:2612",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_puts",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_trace_call",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075760,
      "name": "tracing_gen_ctx_irq_test",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status)
```

```json
{
  "name": "tracing_gen_ctx_irq_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382544,
      "name": "tracing_gen_ctx_irq_test",
      "external": true,
      "loc": "kernel/trace/trace.c:2636",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_puts",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_trace_call",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382544,
      "name": "tracing_gen_ctx_irq_test",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status)
```

```json
{
  "name": "tracing_gen_ctx_irq_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477120,
      "name": "tracing_gen_ctx_irq_test",
      "external": true,
      "loc": "kernel/trace/trace.c:2707",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_array_puts",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_trace_call",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477120,
      "name": "tracing_gen_ctx_irq_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status)
```

```json
{
  "name": "tracing_gen_ctx_irq_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587952,
      "name": "tracing_gen_ctx_irq_test",
      "external": true,
      "loc": "kernel/trace/trace.c:2702",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_array_puts",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_trace_call",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:trace_note",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587952,
      "name": "tracing_gen_ctx_irq_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status)
```
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

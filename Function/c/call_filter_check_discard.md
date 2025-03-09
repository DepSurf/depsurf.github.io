# Function: <code>call_filter_check_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580205664,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205664,
      "name": "call_filter_check_discard.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580205728,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247664,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:309",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247664,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580290656,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:311",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290656,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580303792,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:303",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303792,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580356848,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:303",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356848,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580418672,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:304",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418672,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580474336,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:305",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474336,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580530272,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:307",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530272,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580577872,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577872,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580666995,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:340",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679360,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580657800,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:491",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace",
        "kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670192,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673510,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:493",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668912,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580847736,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:506",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843744,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070832,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:516",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070832,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376960,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:515",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376960,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471552,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:556",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471552,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581808,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:558",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:trace_hwlat_sample",
        "kernel/trace/trace_osnoise.c:__timerlat_dump_stack",
        "kernel/trace/trace_osnoise.c:trace_timerlat_sample",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581808,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491871964,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491867096,
      "name": "call_filter_check_discard.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336491876048,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225810344,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225808592,
      "name": "call_filter_check_discard.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 3225818676,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284939112,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284936512,
      "name": "call_filter_check_discard.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 13835058055284952176,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272163928,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272162176,
      "name": "call_filter_check_discard.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446743936272168042,
      "name": "call_filter_check_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580546672,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546672,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580493504,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493504,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580537920,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537920,
      "name": "call_filter_check_discard",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int call_filter_check_discard(struct trace_event_call * call, void * rec, struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "call_filter_check_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580594400,
      "name": "call_filter_check_discard",
      "external": true,
      "loc": "kernel/trace/trace.c:325",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_mapping",
        "kernel/trace/trace_mmiotrace.c:mmio_trace_rw",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594400,
      "name": "call_filter_check_discard",
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

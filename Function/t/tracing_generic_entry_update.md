# Function: <code>tracing_generic_entry_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry * entry, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580198704,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:1649",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198704,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void tracing_generic_entry_update(struct trace_entry * entry, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580234112,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:1894",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234112,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void tracing_generic_entry_update(struct trace_entry * entry, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275280,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:1938",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275280,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void tracing_generic_entry_update(struct trace_entry * entry, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287616,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2115",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287616,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void tracing_generic_entry_update(struct trace_entry * entry, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580341056,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2118",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341056,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void tracing_generic_entry_update(struct trace_entry * entry, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580402576,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2130",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580402576,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void tracing_generic_entry_update(struct trace_entry * entry, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580457872,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2131",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457872,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580512640,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2314",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512640,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560224,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560224,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580661696,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update",
        "kernel/trace/trace_events_inject.c:parse_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661696,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652480,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2588",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update",
        "kernel/trace/trace_events_inject.c:parse_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652480,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580674047,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:155",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580773207,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:155",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580794206,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:155",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_inject.c:parse_entry"
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
  "name": "tracing_generic_entry_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580848307,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:155",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957095,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:155",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580988558,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:155",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_inject.c:parse_entry"
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
  "name": "tracing_generic_entry_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581076862,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:156",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_puts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581199638,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:156",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581234556,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:156",
      "file": "kernel/trace/trace_events_inject.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581383710,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:156",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_puts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517670,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:156",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555692,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:156",
      "file": "kernel/trace/trace_events_inject.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581478782,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:167",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_array_puts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636198,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:167",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674236,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:167",
      "file": "kernel/trace/trace_events_inject.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581590286,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:167",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_array_puts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750134,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:167",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790380,
      "name": "tracing_generic_entry_update",
      "external": false,
      "loc": "include/linux/trace_events.h:167",
      "file": "kernel/trace/trace_events_inject.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491863992,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491863992,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225795588,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225795588,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284919248,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284919248,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272148730,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272148730,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529024,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529024,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475904,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475904,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580520272,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520272,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```

```json
{
  "name": "tracing_generic_entry_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576720,
      "name": "tracing_generic_entry_update",
      "external": true,
      "loc": "kernel/trace/trace.c:2340",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576720,
      "name": "tracing_generic_entry_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>short unsigned int type</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, flags, pc</code> ➡️ <code>entry, type, flags, pc</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void tracing_generic_entry_update(struct trace_entry * entry, short unsigned int type, long unsigned int flags, int pc)
```
</details>
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

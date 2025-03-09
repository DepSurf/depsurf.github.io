# Function: <code>tracer_tracing_is_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580199703,
      "name": "tracer_tracing_is_on",
      "external": false,
      "loc": "kernel/trace/trace.c:815",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_read"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580237104,
      "name": "tracer_tracing_is_on",
      "external": false,
      "loc": "kernel/trace/trace.c:1050",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_read"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580279564,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1093",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293600,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580293052,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1091",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306880,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580347468,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1091",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359952,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580404533,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1090",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421760,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580459986,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1091",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477504,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580515036,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533328,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580562556,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580928,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580667628,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1315",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_record_tgid",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680160,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580658428,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1466",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_record_tgid",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670992,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580659052,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1463",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_is_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669728,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580833052,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1476",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_is_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844576,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581059316,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1466",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_is_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072720,
      "name": "tracer_tracing_is_on",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364666,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1472",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_is_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379040,
      "name": "tracer_tracing_is_on",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459066,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1523",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_is_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_osnoise.c:osnoise_main",
        "kernel/trace/trace_osnoise.c:notify_new_max_latency",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473632,
      "name": "tracer_tracing_is_on",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568698,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1533",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_wait_pipe",
        "kernel/trace/trace.c:tracing_is_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_osnoise.c:osnoise_main",
        "kernel/trace/trace_osnoise.c:notify_new_max_latency",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584608,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491853592,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491876984,
      "name": "tracer_tracing_is_on",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225798092,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225819628,
      "name": "tracer_tracing_is_on",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284922728,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284953568,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272150754,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_wait_pipe"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272168852,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580531356,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549728,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580478236,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496496,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580522604,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540976,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool tracer_tracing_is_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_is_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580579084,
      "name": "tracer_tracing_is_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1280",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:rb_simple_read"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597520,
      "name": "tracer_tracing_is_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tracer_tracing_is_on(struct trace_array * tr)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

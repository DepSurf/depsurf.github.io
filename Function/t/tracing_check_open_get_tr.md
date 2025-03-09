# Function: <code>tracing_check_open_get_tr</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580575968,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575968,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580665904,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:323",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580677168,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580656704,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:474",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668000,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580657840,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:476",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666720,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580831728,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:489",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841488,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581063948,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:499",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057360,
      "name": "tracing_check_open_get_tr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071581070784,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581368476,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:498",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358304,
      "name": "tracing_check_open_get_tr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071581376896,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581463132,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:539",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453392,
      "name": "tracing_check_open_get_tr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071581471488,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581567903,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:541",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_options",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_file_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:tracing_open_generic"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_open_options",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_file_tr",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563360,
      "name": "tracing_check_open_get_tr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071581581744,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491874136,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491874136,
      "name": "tracing_check_open_get_tr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225817100,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225817100,
      "name": "tracing_check_open_get_tr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284949424,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284949424,
      "name": "tracing_check_open_get_tr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272166462,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272166462,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580544768,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544768,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580491600,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491600,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580536016,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536016,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int tracing_check_open_get_tr(struct trace_array * tr)
```

```json
{
  "name": "tracing_check_open_get_tr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580592496,
      "name": "tracing_check_open_get_tr",
      "external": true,
      "loc": "kernel/trace/trace.c:308",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open_generic_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592496,
      "name": "tracing_check_open_get_tr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int tracing_check_open_get_tr(struct trace_array * tr)
```
</details>
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

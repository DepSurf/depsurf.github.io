# Function: <code>trace_array_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211280,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:304",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211280,
      "name": "trace_array_put",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246112,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:302",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:subsystem_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246112,
      "name": "trace_array_put",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289056,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:304",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:subsystem_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289056,
      "name": "trace_array_put",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580302304,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:296",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:subsystem_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302304,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580355408,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:296",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:subsystem_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355408,
      "name": "trace_array_put",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417088,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:297",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417088,
      "name": "trace_array_put",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472752,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:298",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472752,
      "name": "trace_array_put",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580528320,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:300",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:system_tr_open",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528320,
      "name": "trace_array_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580575008,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575008,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580679088,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:312",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init_instances"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666096,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580669913,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:463",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init_instances"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656896,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580668633,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:465",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658032,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580843433,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:478",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832784,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581064134,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:488",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052880,
      "name": "trace_array_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071581058848,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581368662,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:487",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354416,
      "name": "trace_array_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071581364336,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619584381,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:528",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448672,
      "name": "trace_array_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071581458832,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621887727,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:530",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:tracing_release_options",
        "kernel/trace/trace.c:tracing_release_options",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:tracing_single_release_file_tr",
        "kernel/trace/trace.c:tracing_single_release_file_tr",
        "kernel/trace/trace.c:tracing_open_file_tr",
        "kernel/trace/trace.c:tracing_open_file_tr"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars",
        "kernel/trace/trace_boot.c:trace_boot_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558480,
      "name": "trace_array_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071581568976,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491873016,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491873016,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225816152,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225816152,
      "name": "trace_array_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284947952,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284947952,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272165492,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272165492,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543808,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543808,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580490640,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490640,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535056,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535056,
      "name": "trace_array_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void trace_array_put(struct trace_array * this_tr)
```

```json
{
  "name": "trace_array_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591536,
      "name": "trace_array_put",
      "external": true,
      "loc": "kernel/trace/trace.c:301",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:tracing_release_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_single_release_tr",
        "kernel/trace/trace.c:tracing_release_generic_tr",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events.c:subsystem_release",
        "kernel/trace/trace_events.c:subsystem_open",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591536,
      "name": "trace_array_put",
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

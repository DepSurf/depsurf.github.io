# Function: <code>kstrtoul_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047968,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:340",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047968,
      "name": "kstrtoul_from_user",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341776,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:404",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341776,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583467152,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:400",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467152,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583489424,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:402",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489424,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670464,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670464,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583888240,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888240,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972480,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972480,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153696,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153696,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276320,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276320,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684576,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684576,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584802144,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:400",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802144,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845920,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:407",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845920,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585265872,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:408",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585265872,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:424",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111936,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:424",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097792,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:424",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357856,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:424",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_subbuf_size_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587644176,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496161752,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496161752,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229481308,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229481308,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290425744,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290425744,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275213052,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275213052,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584245056,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245056,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584180256,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180256,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228816,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228816,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kstrtoul_from_user(const char * s, size_t count, unsigned int base, long unsigned int * res)
```

```json
{
  "name": "kstrtoul_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333648,
      "name": "kstrtoul_from_user",
      "external": true,
      "loc": "lib/kstrtox.c:403",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_write",
        "kernel/trace/trace.c:buffer_percent_write",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:trace_options_core_write",
        "kernel/trace/trace.c:trace_options_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_entries_write",
        "kernel/trace/trace.c:tracing_max_lat_write",
        "kernel/trace/trace.c:tracing_thresh_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_functions_graph.c:graph_depth_write",
        "kernel/trace/trace_events.c:system_enable_write",
        "kernel/trace/trace_events.c:event_enable_write",
        "drivers/scsi/sg.c:sg_proc_write_dressz",
        "drivers/scsi/sg.c:sg_proc_write_adio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333648,
      "name": "kstrtoul_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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

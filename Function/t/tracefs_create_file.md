# Function: <code>tracefs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118944,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:392",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118944,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582337264,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:392",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337264,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428080,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:392",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428080,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511616,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:390",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511616,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582663232,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:390",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663232,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582856720,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:390",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856720,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964992,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:390",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964992,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145904,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:386",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145904,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251968,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251968,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583579056,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:390",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579056,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699472,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:390",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_profile_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699472,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724352,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:392",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace.c:tracing_init_tracefs_percpu",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724352,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584085520,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:465",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085520,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679536,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:465",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679536,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364736,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:480",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_register_monitor",
        "kernel/trace/rv/rv.c:rv_register_monitor",
        "kernel/trace/rv/rv_reactors.c:init_rv_reactors",
        "kernel/trace/rv/rv_reactors.c:init_rv_reactors",
        "kernel/trace/rv/rv_reactors.c:reactor_populate_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364736,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585595136,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:480",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init",
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_register_monitor",
        "kernel/trace/rv/rv.c:rv_register_monitor",
        "kernel/trace/rv/rv_reactors.c:init_rv_reactors",
        "kernel/trace/rv/rv_reactors.c:init_rv_reactors",
        "kernel/trace/rv/rv_reactors.c:reactor_populate_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595136,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585836016,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:553",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events_synth.c:trace_events_synth_init",
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_init_interface",
        "kernel/trace/rv/rv.c:rv_register_monitor",
        "kernel/trace/rv/rv.c:rv_register_monitor",
        "kernel/trace/rv/rv_reactors.c:init_rv_reactors",
        "kernel/trace/rv/rv_reactors.c:init_rv_reactors",
        "kernel/trace/rv/rv_reactors.c:reactor_populate_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836016,
      "name": "tracefs_create_file",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494979248,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494979248,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228385228,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228385228,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288860528,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288860528,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274279360,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274279360,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583220704,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220704,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157856,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157856,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583204736,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583204736,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
struct dentry * tracefs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "tracefs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298624,
      "name": "tracefs_create_file",
      "external": true,
      "loc": "fs/tracefs/inode.c:387",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/trace.c:trace_create_file",
        "kernel/trace/trace_stat.c:register_stat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events_hist.c:trace_events_hist_init",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298624,
      "name": "tracefs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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

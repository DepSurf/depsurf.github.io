# Function: <code>trace_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231008,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:6311",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/trace.c:create_trace_option_files",
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
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231008,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268400,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:6714",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268400,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311424,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:6997",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311424,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325024,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:7361",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325024,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378192,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:7364",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378192,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:7452",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443992,
      "name": "trace_create_file.cold.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580440048,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:7474",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499688,
      "name": "trace_create_file.cold.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580495648,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:7959",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556198,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580551712,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603772,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580599376,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580674544,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8213",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:tracing_init_tracefs_percpu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702180,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580699632,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580665296,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8287",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:tracing_init_tracefs_percpu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591319809,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580690416,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580664000,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8623",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:tracing_init_tracefs_percpu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591262121,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580694624,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580837999,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8787",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:create_trace_option_files"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592171307,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580871184,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581067039,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8819",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:create_trace_option_files"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593944884,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581101616,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627816728,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8914",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:create_trace_option_files"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409520,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619580488,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:9077",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:create_trace_option_files"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_profile_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504496,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621883864,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:9159",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/trace/trace.c:create_trace_option_files"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_profile_tracefs",
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:event_trace_init",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_dynevent.c:init_dynamic_event",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615984,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491897944,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491897944,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225840220,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225840220,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284984256,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284984256,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272186242,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272186242,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572572,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580568176,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519212,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580514848,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580563820,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580559424,
      "name": "trace_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct dentry * trace_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "trace_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_create_file",
      "external": true,
      "loc": "kernel/trace/trace.c:8010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel",
        "kernel/trace/ftrace.c:ftrace_init_tracefs",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/ftrace.c:ftrace_create_filter_files",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:tracer_init_tracefs",
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
        "kernel/trace/trace_printk.c:init_trace_printk_function_export",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_stack.c:stack_trace_init",
        "kernel/trace/trace_functions_graph.c:init_graph_tracefs",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:create_event_toplevel_files",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_events.c:event_create_dir",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace",
        "kernel/trace/trace_uprobe.c:init_uprobe_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620540,
      "name": "trace_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580616144,
      "name": "trace_create_file",
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

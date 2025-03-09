# Function: <code>tracer_tracing_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580199655,
      "name": "tracer_tracing_off",
      "external": false,
      "loc": "kernel/trace/trace.c:772",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:trace_init"
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
  "name": "tracer_tracing_off",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595283771,
      "name": "tracer_tracing_off",
      "external": false,
      "loc": "kernel/trace/trace.c:1007",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595530496,
      "name": "tracer_tracing_off",
      "external": false,
      "loc": "kernel/trace/trace.c:1050",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596450436,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1048",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306768,
      "name": "tracer_tracing_off",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602776403,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1048",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359856,
      "name": "tracer_tracing_off",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602950460,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1047",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421664,
      "name": "tracer_tracing_off",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604748374,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1048",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477408,
      "name": "tracer_tracing_off",
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604849624,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1219",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533216,
      "name": "tracer_tracing_off",
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604883722,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580816,
      "name": "tracer_tracing_off",
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580667669,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1269",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680112,
      "name": "tracer_tracing_off",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580658469,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1420",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670944,
      "name": "tracer_tracing_off",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580659093,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1417",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669680,
      "name": "tracer_tracing_off",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580833093,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1430",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844528,
      "name": "tracer_tracing_off",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581059357,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1420",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072672,
      "name": "tracer_tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364707,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1426",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378976,
      "name": "tracer_tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459107,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1477",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:timerlat_irq",
        "kernel/trace/trace_osnoise.c:trace_sched_migrate_callback",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473568,
      "name": "tracer_tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568739,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1487",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:timerlat_irq",
        "kernel/trace/trace_osnoise.c:trace_sched_migrate_callback",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584544,
      "name": "tracer_tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510921076,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491876856,
      "name": "tracer_tracing_off",
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243409200,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:ftrace_traceoff_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225819508,
      "name": "tracer_tracing_off",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302561708,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284953360,
      "name": "tracer_tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270655400,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272168746,
      "name": "tracer_tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604789179,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549616,
      "name": "tracer_tracing_off",
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604758107,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496384,
      "name": "tracer_tracing_off",
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604866366,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540864,
      "name": "tracer_tracing_off",
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
void tracer_tracing_off(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604887903,
      "name": "tracer_tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1237",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_free_buffer_release",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597408,
      "name": "tracer_tracing_off",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tracer_tracing_off(struct trace_array * tr)
```
</details>
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

# Function: <code>tracing_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580199648,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:797",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:trace_init"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:update_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199648,
      "name": "tracing_off",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595283771,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1032",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:update_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235472,
      "name": "tracing_off",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595530496,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1075",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_functions.c:ftrace_traceoff",
        "kernel/trace/trace_functions.c:update_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276912,
      "name": "tracing_off",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596450436,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1073",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289520,
      "name": "tracing_off",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602776403,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1073",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342960,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602950460,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1072",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403984,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604748374,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1073",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459280,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604849624,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1244",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514336,
      "name": "tracing_off",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604883722,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580561888,
      "name": "tracing_off",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580686105,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1294",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663376,
      "name": "tracing_off",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580676905,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1445",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654176,
      "name": "tracing_off",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580679625,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1442",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655904,
      "name": "tracing_off",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580854121,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1455",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829984,
      "name": "tracing_off",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581083205,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1445",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056112,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581390485,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1451",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358016,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581485061,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1502",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452512,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581595909,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1512",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:disable_trace_on_warning"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562320,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510921076,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491852792,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243409200,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225797344,
      "name": "tracing_off",
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302561708,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284921616,
      "name": "tracing_off",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270655400,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272150226,
      "name": "tracing_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604789179,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530688,
      "name": "tracing_off",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604758107,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477568,
      "name": "tracing_off",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604866366,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521936,
      "name": "tracing_off",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_off()
```

```json
{
  "name": "tracing_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604887903,
      "name": "tracing_off",
      "external": true,
      "loc": "kernel/trace/trace.c:1262",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:disable_trace_on_warning",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/trace_events_trigger.c:traceoff_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578416,
      "name": "tracing_off",
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

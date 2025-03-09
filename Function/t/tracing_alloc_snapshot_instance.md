# Function: <code>tracing_alloc_snapshot_instance</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580413244,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:952",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413088,
      "name": "tracing_alloc_snapshot_instance.part.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580421632,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468796,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:953",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468640,
      "name": "tracing_alloc_snapshot_instance.part.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580477376,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580524137,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1010",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523680,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580533184,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580571673,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571216,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580580784,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580665705,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1060",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680048,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580656505,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1211",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger",
        "kernel/trace/trace_boot.c:trace_boot_enable_tracer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670880,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580657641,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1208",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669616,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832421,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1221",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592170050,
      "name": "tracing_alloc_snapshot_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580844448,
      "name": "tracing_alloc_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581060797,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1211",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593943768,
      "name": "tracing_alloc_snapshot_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581072592,
      "name": "tracing_alloc_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581366445,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1212",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596004725,
      "name": "tracing_alloc_snapshot_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581378880,
      "name": "tracing_alloc_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581460157,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1263",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596523310,
      "name": "tracing_alloc_snapshot_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581473472,
      "name": "tracing_alloc_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581569712,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1265",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger",
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597424039,
      "name": "tracing_alloc_snapshot_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581583728,
      "name": "tracing_alloc_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491862156,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491861992,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336491876816,
      "name": "tracing_alloc_snapshot_instance",
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
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225806364,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225806188,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3225819468,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284935252,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_alloc_snapshot"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_alloc_snapshot",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284934928,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055284953312,
      "name": "tracing_alloc_snapshot_instance",
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
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272159334,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272158958,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936272168712,
      "name": "tracing_alloc_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580540473,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540016,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580549584,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580487321,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486864,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580496352,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580531721,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531264,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580540832,
      "name": "tracing_alloc_snapshot_instance",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_alloc_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580588201,
      "name": "tracing_alloc_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_trace_snapshot_callback",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace_events_trigger.c:register_snapshot_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587744,
      "name": "tracing_alloc_snapshot_instance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580597376,
      "name": "tracing_alloc_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int tracing_alloc_snapshot_instance(struct trace_array * tr)
```
</details>
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

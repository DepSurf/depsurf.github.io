# Function: <code>tracer_tracing_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580199607,
      "name": "tracer_tracing_on",
      "external": false,
      "loc": "kernel/trace/trace.c:506",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_on",
        "kernel/trace/trace.c:rb_simple_write"
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
  "name": "tracer_tracing_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580235976,
      "name": "tracer_tracing_on",
      "external": false,
      "loc": "kernel/trace/trace.c:741",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
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
  "name": "tracer_tracing_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580277416,
      "name": "tracer_tracing_on",
      "external": false,
      "loc": "kernel/trace/trace.c:768",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580290049,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:760",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306720,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580343489,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:760",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359808,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580404677,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:759",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421584,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580460128,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:760",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477328,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580515174,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:764",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533136,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580562694,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580736,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580667766,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:803",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680000,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580658566,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:954",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670832,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580659190,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:957",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669568,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580833190,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:970",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844400,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581059469,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:958",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072544,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364834,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:957",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378816,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459234,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:998",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473408,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568866,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:1000",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count",
        "kernel/trace/trace_events_trigger.c:traceon_count_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583664,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491853736,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491876768,
      "name": "tracer_tracing_on",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225798264,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon",
        "kernel/trace/trace_functions.c:ftrace_traceon_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225819420,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284922912,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284953232,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272150870,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272168670,
      "name": "tracer_tracing_on",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580531494,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549536,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580478374,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496304,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580522742,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540784,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
```

```json
{
  "name": "tracer_tracing_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580579222,
      "name": "tracer_tracing_on",
      "external": true,
      "loc": "kernel/trace/trace.c:782",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:rb_simple_write",
        "kernel/trace/trace.c:tracing_on"
      ],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_traceon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597328,
      "name": "tracer_tracing_on",
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
void tracer_tracing_on(struct trace_array * tr)
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

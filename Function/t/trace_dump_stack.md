# Function: <code>trace_dump_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219776,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:1900",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_functions.c:ftrace_stacktrace_count",
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219776,
      "name": "trace_dump_stack",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256752,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2272",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_stacktrace_count",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256752,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580299184,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2496",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions.c:ftrace_stacktrace_count",
        "kernel/trace/trace_functions.c:ftrace_stacktrace",
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580299184,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312656,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2702",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312656,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365792,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2712",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365792,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580427200,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2713",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427200,
      "name": "trace_dump_stack",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580475712,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2714",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475712,
      "name": "trace_dump_stack",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580531392,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2891",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531392,
      "name": "trace_dump_stack",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580578992,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578992,
      "name": "trace_dump_stack",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580669184,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3028",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669184,
      "name": "trace_dump_stack",
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580659984,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3046",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659984,
      "name": "trace_dump_stack",
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673792,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3067",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673792,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580848064,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3127",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592170149,
      "name": "trace_dump_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580848016,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581077870,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3125",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593943884,
      "name": "trace_dump_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581077808,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581384110,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3149",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596004831,
      "name": "trace_dump_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581384048,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581478128,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3240",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478128,
      "name": "trace_dump_stack",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581588960,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:3217",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588960,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491871024,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491871024,
      "name": "trace_dump_stack",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225809944,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225809944,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284938608,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284938608,
      "name": "trace_dump_stack",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272163518,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272163518,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580547792,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547792,
      "name": "trace_dump_stack",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580494608,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494608,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580539040,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539040,
      "name": "trace_dump_stack",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void trace_dump_stack(int skip)
```

```json
{
  "name": "trace_dump_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580595552,
      "name": "trace_dump_stack",
      "external": true,
      "loc": "kernel/trace/trace.c:2917",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:stacktrace_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595552,
      "name": "trace_dump_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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

# Function: <code>tracing_snapshot_instance</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580310576,
      "name": "tracing_snapshot_instance",
      "external": false,
      "loc": "kernel/trace/trace.c:897",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot",
        "kernel/trace/trace.c:tracing_snapshot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580310576,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580363712,
      "name": "tracing_snapshot_instance",
      "external": false,
      "loc": "kernel/trace/trace.c:897",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot",
        "kernel/trace/trace.c:tracing_snapshot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363712,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425152,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:896",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot",
        "kernel/trace/trace.c:tracing_snapshot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425152,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480896,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:897",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot",
        "kernel/trace/trace.c:tracing_snapshot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480896,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580537213,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:931",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537072,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580584749,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584608,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580683437,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:981",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:snapshot_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683248,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580674269,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1132",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:snapshot_count_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674080,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580675485,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1129",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675296,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580849613,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1142",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849408,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617142219,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1132",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_boot_snapshot",
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079888,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627820104,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1131",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_boot_snapshot",
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386832,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619583865,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1182",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_boot_snapshot",
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481440,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621887202,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:1184",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_boot_snapshot",
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592288,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491882256,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491882072,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225824260,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225824064,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284960808,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284960560,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272172494,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272172322,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580553549,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553408,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580500253,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500112,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580544797,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544656,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
```

```json
{
  "name": "tracing_snapshot_instance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580601373,
      "name": "tracing_snapshot_instance",
      "external": true,
      "loc": "kernel/trace/trace.c:949",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:ftrace_count_snapshot",
        "kernel/trace/trace.c:ftrace_snapshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601232,
      "name": "tracing_snapshot_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void tracing_snapshot_instance(struct trace_array * tr)
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

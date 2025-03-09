# Function: <code>event_define_fields</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "event_define_fields",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580763191,
      "name": "event_define_fields",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2129",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:event_trace_add_tracer",
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_add_event_call",
        "kernel/trace/trace_events.c:event_create_dir"
      ],
      "caller_func": [
        "kernel/trace/trace_events.c:event_trace_add_tracer",
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_add_event_call",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755728,
      "name": "event_define_fields.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071591321893,
      "name": "event_define_fields.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int event_define_fields(struct trace_event_call * call)
```

```json
{
  "name": "event_define_fields",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580763087,
      "name": "event_define_fields",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2340",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_trace_add_tracer",
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_add_event_call",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763024,
      "name": "event_define_fields",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071591263714,
      "name": "event_define_fields.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int event_define_fields(struct trace_event_call * call)
```

```json
{
  "name": "event_define_fields",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946991,
      "name": "event_define_fields",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2342",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:__trace_add_new_event",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946928,
      "name": "event_define_fields",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071592174623,
      "name": "event_define_fields.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int event_define_fields(struct trace_event_call * call)
```

```json
{
  "name": "event_define_fields",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581188784,
      "name": "event_define_fields",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2361",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:__trace_add_new_event",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188784,
      "name": "event_define_fields",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int event_define_fields(struct trace_event_call * call)
```

```json
{
  "name": "event_define_fields",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581502256,
      "name": "event_define_fields",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2381",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:__trace_add_new_event",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502256,
      "name": "event_define_fields",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int event_define_fields(struct trace_event_call * call)
```

```json
{
  "name": "event_define_fields",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620320,
      "name": "event_define_fields",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2375",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:__trace_add_new_event",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620320,
      "name": "event_define_fields",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int event_define_fields(struct trace_event_call * call)
```

```json
{
  "name": "event_define_fields",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581733504,
      "name": "event_define_fields",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2438",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:__trace_early_add_events",
        "kernel/trace/trace_events.c:__trace_add_new_event",
        "kernel/trace/trace_events.c:event_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733504,
      "name": "event_define_fields",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int event_define_fields(struct trace_event_call * call)
```
</details>
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

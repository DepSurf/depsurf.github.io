# Function: <code>ring_buffer_iter_advance</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580640400,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4408",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640400,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580630848,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4954",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630848,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634800,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5061",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634800,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807440,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5061",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807440,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034480,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5103",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034480,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581334736,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5209",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334736,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581429712,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5216",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581429712,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```

```json
{
  "name": "ring_buffer_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538864,
      "name": "ring_buffer_iter_advance",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5124",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_iter_reset",
        "kernel/trace/trace.c:trace_find_next_entry_inc",
        "kernel/trace/trace_functions_graph.c:print_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538864,
      "name": "ring_buffer_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ring_buffer_iter_advance(struct ring_buffer_iter * iter)
```
</details>
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

# Function: <code>__buffer_unlock_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580216390,
      "name": "__buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/trace.c:1689",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219584,
      "name": "__buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void __buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580252976,
      "name": "__buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/trace.c:2052",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace_functions_graph.c:__trace_graph_return",
        "kernel/trace/trace_functions_graph.c:__trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252976,
      "name": "__buffer_unlock_commit",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580280773,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:799",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580293621,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:791",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580344949,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:791",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580406405,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:790",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580461813,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:791",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580518207,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:795",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580565551,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580669023,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:834",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580659823,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:985",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580674170,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:988",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580848430,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:1001",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581076984,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:989",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_puts"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581383832,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:988",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_puts"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581478911,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:1029",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_array_puts"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581590418,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:1031",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_array_puts"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491867972,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225811240,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284945796,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272160380,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580534351,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580481225,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580525599,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__buffer_unlock_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580582079,
      "name": "__buffer_unlock_commit",
      "external": false,
      "loc": "kernel/trace/trace.c:813",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void __buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```
</details>
</li>
</ul>

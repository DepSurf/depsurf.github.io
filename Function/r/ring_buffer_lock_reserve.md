# Function: <code>ring_buffer_lock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580187840,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2832",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187840,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229504,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2827",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229504,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263760,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2796",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263760,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276160,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2798",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276160,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329968,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2790",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329968,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390640,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2923",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390640,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445632,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2986",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445632,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580499392,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2963",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499392,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 983
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580547296,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547296,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647952,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3033",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647952,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580638672,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3584",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580638672,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633488,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3671",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633488,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3671",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167712,
      "name": "ring_buffer_lock_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071580806048,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3709",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593941274,
      "name": "ring_buffer_lock_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071581031328,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3788",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003356,
      "name": "ring_buffer_lock_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071581332032,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3791",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_array_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596521949,
      "name": "ring_buffer_lock_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071581426768,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct trace_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3695",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve",
        "kernel/trace/trace.c:__trace_array_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597422501,
      "name": "ring_buffer_lock_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071581536096,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491843168,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491843168,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1128
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225789388,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225789388,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1340
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284903504,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284903504,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1420
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
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272139724,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272139724,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580516096,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580516096,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580464816,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464816,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507344,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507344,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * ring_buffer_lock_reserve(struct ring_buffer * buffer, long unsigned int length)
```

```json
{
  "name": "ring_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580564320,
      "name": "ring_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2964",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564320,
      "name": "ring_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer * buffer</code> ➡️ <code>struct trace_buffer * buffer</code>
</li>
</ul>
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

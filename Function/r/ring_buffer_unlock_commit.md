# Function: <code>ring_buffer_unlock_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191712,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2650",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191712,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225296,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2644",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225296,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580260400,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2613",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260400,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274496,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2615",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274496,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327648,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2608",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327648,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388928,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2737",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388928,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580455120,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2800",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580455120,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580509872,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2777",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509872,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557440,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557440,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644944,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2847",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644944,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635664,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3180",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635664,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636496,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3263",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636496,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3263",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167530,
      "name": "ring_buffer_unlock_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071580803280,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3301",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593941457,
      "name": "ring_buffer_unlock_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581032272,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3381",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003593,
      "name": "ring_buffer_unlock_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581342608,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3384",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_array_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596522186,
      "name": "ring_buffer_unlock_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581436944,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
int ring_buffer_unlock_commit(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3204",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_array_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597422833,
      "name": "ring_buffer_unlock_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581546192,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491844784,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491844784,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225792328,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
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
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225792328,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284915088,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284915088,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272146414,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272146414,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526240,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526240,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580473120,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473120,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580517488,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517488,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ring_buffer_unlock_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_unlock_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573856,
      "name": "ring_buffer_unlock_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2778",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573856,
      "name": "ring_buffer_unlock_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ring_buffer_event * event</code>
</li>
</ul>
</details>
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

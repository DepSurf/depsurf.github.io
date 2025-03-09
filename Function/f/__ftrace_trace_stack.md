# Function: <code>__ftrace_trace_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216176,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:1798",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_dump_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216176,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253040,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2163",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_dump_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253040,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290752,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2387",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_dump_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290752,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580303888,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2564",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_dump_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303888,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356944,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2572",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_dump_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356944,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580418768,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2584",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_dump_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418768,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474432,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2585",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474432,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580530368,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2778",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530368,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580577968,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577968,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void __ftrace_trace_stack(struct trace_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580666256,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2915",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666256,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void __ftrace_trace_stack(struct trace_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657056,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2938",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657056,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void __ftrace_trace_stack(struct trace_buffer * buffer, unsigned int trace_ctx, int skip, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580658192,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2959",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658192,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void __ftrace_trace_stack(struct trace_buffer * buffer, unsigned int trace_ctx, int skip, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831920,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:3019",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831920,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void __ftrace_trace_stack(struct trace_buffer * buffer, unsigned int trace_ctx, int skip, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070976,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:3017",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070976,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
void __ftrace_trace_stack(struct trace_buffer * buffer, unsigned int trace_ctx, int skip, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377120,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:3041",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377120,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void __ftrace_trace_stack(struct trace_buffer * buffer, unsigned int trace_ctx, int skip, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471712,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:3112",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_array_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471712,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void __ftrace_trace_stack(struct trace_buffer * buffer, unsigned int trace_ctx, int skip, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581968,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:3106",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:__trace_array_puts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581968,
      "name": "__ftrace_trace_stack",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491870088,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491870088,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225808720,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225808720,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284936736,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284936736,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272162320,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272162320,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546768,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546768,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580493600,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493600,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538016,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538016,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void __ftrace_trace_stack(struct ring_buffer * buffer, long unsigned int flags, int skip, int pc, struct pt_regs * regs)
```

```json
{
  "name": "__ftrace_trace_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580594496,
      "name": "__ftrace_trace_stack",
      "external": false,
      "loc": "kernel/trace/trace.c:2804",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594496,
      "name": "__ftrace_trace_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int trace_ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int pc</code>
</li>
<li>
<b>Param reordered. </b>
<code>buffer, flags, skip, pc, regs</code> ➡️ <code>buffer, trace_ctx, skip, regs</code>
</li>
</ul>
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

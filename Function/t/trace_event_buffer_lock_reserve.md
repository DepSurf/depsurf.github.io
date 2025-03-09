# Function: <code>trace_event_buffer_lock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580216016,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:1710",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216016,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252064,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2069",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252064,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276480,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2082",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276480,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289056,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2259",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289056,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342496,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2262",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342496,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580404960,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2274",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404960,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580460416,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2275",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460416,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515456,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2459",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515456,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580562976,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562976,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580661840,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2589",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661840,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652624,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2733",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652624,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647408,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2742",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647408,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820400,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2766",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820400,
      "name": "trace_event_buffer_lock_reserve",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044848,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2759",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044848,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348096,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2783",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348096,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442272,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2854",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442272,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct trace_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, unsigned int trace_ctx)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551552,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2848",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551552,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491864120,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491864120,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225798624,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225798624,
      "name": "trace_event_buffer_lock_reserve",
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284923408,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284923408,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272151112,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272151112,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531776,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531776,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478656,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478656,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580523024,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523024,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct ring_buffer_event * trace_event_buffer_lock_reserve(struct ring_buffer * * current_rb, struct trace_event_file * trace_file, int type, long unsigned int len, long unsigned int flags, int pc)
```

```json
{
  "name": "trace_event_buffer_lock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580579504,
      "name": "trace_event_buffer_lock_reserve",
      "external": true,
      "loc": "kernel/trace/trace.c:2485",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_reserve",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580579504,
      "name": "trace_event_buffer_lock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
<code>struct ring_buffer * * current_rb</code> ➡️ <code>struct trace_buffer * * current_rb</code>
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

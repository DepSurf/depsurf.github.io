# Function: <code>ring_buffer_discard_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580192320,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2933",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_current_buffer_discard_commit",
        "kernel/trace/trace_events.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192320,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225936,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2928",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225936,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1033
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270464,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2897",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270464,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1106
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580282944,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2899",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282944,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1030
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336384,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:2891",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336384,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580398624,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3024",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398624,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1034
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451104,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3087",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451104,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505472,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3064",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505472,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580552320,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552320,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641248,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3134",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:ftrace_trace_userstack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641248,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580631504,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3685",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631504,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635456,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3772",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635456,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3772",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167898,
      "name": "ring_buffer_discard_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580808096,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1042
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3810",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:call_filter_check_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593941553,
      "name": "ring_buffer_discard_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581032784,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3889",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:call_filter_check_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003539,
      "name": "ring_buffer_discard_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581332992,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3892",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:call_filter_check_discard",
        "kernel/trace/trace_events_user.c:user_event_ftrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596522132,
      "name": "ring_buffer_discard_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581427760,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1127
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
void ring_buffer_discard_commit(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3796",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:call_filter_check_discard",
        "kernel/trace/trace_events_user.c:user_event_ftrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597422684,
      "name": "ring_buffer_discard_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071581537120,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1102
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491838120,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491838120,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1408
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225785608,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225785608,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1460
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284907456,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284907456,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1612
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272143464,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272143464,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521120,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521120,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469552,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469552,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580512368,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512368,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
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
void ring_buffer_discard_commit(struct ring_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_discard_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580568704,
      "name": "ring_buffer_discard_commit",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:3065",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568704,
      "name": "ring_buffer_discard_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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

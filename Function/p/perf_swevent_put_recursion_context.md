# Function: <code>perf_swevent_put_recursion_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580429722,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:6696",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event",
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435776,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580463960,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:7290",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508848,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580527592,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:7403",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572976,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580558875,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:7626",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603584,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580641139,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:7623",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684336,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580770912,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8005",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816336,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580839427,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8014",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882992,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580934386,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8318",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980192,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580988322,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034320,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581168632,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8984",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214304,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581208573,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:9250",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257296,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581224374,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:9380",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275312,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581466053,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:9499",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516464,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581814370,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:9434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863424,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582242340,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:9759",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_task",
        "kernel/events/core.c:perf_pending_irq"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290672,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582443506,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:9788",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_task",
        "kernel/events/core.c:perf_pending_irq"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_events_user.c:user_event_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491376,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582611682,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:9858",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_task",
        "kernel/events/core.c:perf_pending_irq"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_events_user.c:user_event_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659824,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492386760,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_trace_run_bpf_submit",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492386760,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226274520,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226275064,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285646748,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285647504,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272457154,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272498064,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580957122,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003168,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580904130,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949328,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580948370,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994368,
      "name": "perf_swevent_put_recursion_context",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void perf_swevent_put_recursion_context(int rctx)
```

```json
{
  "name": "perf_swevent_put_recursion_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581010716,
      "name": "perf_swevent_put_recursion_context",
      "external": true,
      "loc": "kernel/events/core.c:8434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055424,
      "name": "perf_swevent_put_recursion_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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

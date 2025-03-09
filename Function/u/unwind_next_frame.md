# Function: <code>unwind_next_frame</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579278224,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:160",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278224,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275056,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:264",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275056,
      "name": "unwind_next_frame.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071579275584,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293616,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:282",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293616,
      "name": "unwind_next_frame.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071579294144,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306062,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:282",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305472,
      "name": "unwind_next_frame.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071579306409,
      "name": "unwind_next_frame.part.5.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579305904,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579330624,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:282",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330000,
      "name": "unwind_next_frame.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071579330998,
      "name": "unwind_next_frame.part.6.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579330448,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345888,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:260",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345280,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071579346257,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579345712,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350224,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:260",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349616,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071579350589,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579350048,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579379964,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:254",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379344,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071579380317,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579379792,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378604,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:254",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377984,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071591265308,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579378432,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382220,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:254",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381600,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071591207513,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579382048,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579443916,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:254",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443248,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071592080854,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071579443744,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:253",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593848193,
      "name": "unwind_next_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071579513488,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:264",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595967955,
      "name": "unwind_next_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579612752,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:264",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596485572,
      "name": "unwind_next_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579625360,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:264",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597382182,
      "name": "unwind_next_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579654416,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346128,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:260",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345520,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071579346493,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579345952,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579278336,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:260",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277728,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071579278701,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579278160,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346048,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:260",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345440,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071579346413,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579345872,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```

```json
{
  "name": "unwind_next_frame",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579354496,
      "name": "unwind_next_frame",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:260",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk",
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353888,
      "name": "unwind_next_frame.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071579354861,
      "name": "unwind_next_frame.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579354320,
      "name": "unwind_next_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool unwind_next_frame(struct unwind_state * state)
```
</details>
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

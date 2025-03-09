# Function: <code>sched_clock_stable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579570608,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:83",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:__set_sched_clock_stable",
        "kernel/sched/clock.c:__clear_sched_clock_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:cpu_clock"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570800,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581735,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:84",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:__clear_sched_clock_stable",
        "kernel/sched/clock.c:__set_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581936,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579607911,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:84",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:__clear_sched_clock_stable",
        "kernel/sched/clock.c:__set_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608112,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579586096,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:123",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585840,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579615525,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:123",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615280,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579645872,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:111",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645632,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683472,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:107",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683232,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717248,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717024,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579759680,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759456,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579793232,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/ring_buffer.c:rb_handle_timestamp",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792976,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784080,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/ring_buffer.c:rb_add_timestamp",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783824,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792192,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791936,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887968,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/trace.c:late_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887728,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580176435,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:106",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/trace/trace.c:late_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176016,
      "name": "sched_clock_stable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580359155,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:106",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/trace/trace.c:late_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361600,
      "name": "sched_clock_stable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580429824,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:106",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/trace/trace.c:late_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429200,
      "name": "sched_clock_stable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580489376,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:106",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/trace/ring_buffer.c:rb_add_timestamp",
        "kernel/trace/trace.c:late_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488720,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_stable",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2408",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "sched_clock_stable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_stable",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2408",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "sched_clock_stable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_stable",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2408",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "sched_clock_stable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_stable",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2408",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579735600,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735376,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664400,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664176,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720048,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719824,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int sched_clock_stable()
```

```json
{
  "name": "sched_clock_stable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579767392,
      "name": "sched_clock_stable",
      "external": true,
      "loc": "kernel/sched/clock.c:108",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:clear_sched_clock_stable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace.c:tracing_set_default_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767168,
      "name": "sched_clock_stable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int sched_clock_stable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int sched_clock_stable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int sched_clock_stable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int sched_clock_stable()
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

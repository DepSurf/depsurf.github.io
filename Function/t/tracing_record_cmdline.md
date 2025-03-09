# Function: <code>tracing_record_cmdline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tracing_record_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580215184,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:1636",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_sched_switch.c:probe_sched_switch",
        "kernel/trace/trace_sched_switch.c:probe_sched_switch",
        "kernel/trace/trace_sched_switch.c:probe_sched_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215184,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void tracing_record_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580251232,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:1881",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_sched_switch.c:probe_sched_wakeup",
        "kernel/trace/trace_sched_switch.c:probe_sched_switch",
        "kernel/trace/trace_sched_switch.c:probe_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251232,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void tracing_record_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580296608,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:1925",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace_sched_switch.c:probe_sched_wakeup",
        "kernel/trace/trace_sched_switch.c:probe_sched_switch",
        "kernel/trace/trace_sched_switch.c:probe_sched_switch",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296608,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580310315,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2092",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311360,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580363451,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2095",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364496,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580424888,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2107",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425904,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480632,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2108",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481648,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580536381,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2291",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537504,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580583917,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585040,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580682533,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2421",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683856,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673358,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2565",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674688,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580662483,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2576",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672912,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580836325,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2590",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847088,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581064878,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2581",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075616,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581369707,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2605",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382368,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581464363,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2676",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476944,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581572875,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2671",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587776,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491881300,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491882784,
      "name": "tracing_record_cmdline",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225823240,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225824580,
      "name": "tracing_record_cmdline",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284959436,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284961296,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272171654,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272172908,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580552717,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553840,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499485,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500544,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580543965,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545088,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tracing_record_cmdline(struct task_struct * task)
```

```json
{
  "name": "tracing_record_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580600539,
      "name": "tracing_record_cmdline",
      "external": true,
      "loc": "kernel/trace/trace.c:2317",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__update_max_tr"
      ],
      "caller_func": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/blktrace.c:__blk_add_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601664,
      "name": "tracing_record_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
</details>
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

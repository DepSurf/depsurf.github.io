# Function: <code>perf_event_sched_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580406144,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2058",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580406144,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480352,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2207",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480352,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543248,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2245",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543248,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580577888,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2289",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577888,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657360,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2223",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657360,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759120,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759120,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825584,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825584,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920224,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2423",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920224,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973680,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973680,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178992,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2657",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178992,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224208,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2692",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224208,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230784,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2694",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230784,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489328,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2733",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489328,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581834864,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2645",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834864,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582263545,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2639",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched"
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
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582464345,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2639",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched"
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
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582631901,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2677",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492327544,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492327544,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226224692,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226224692,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285581008,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285581008,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272458894,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272458894,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942480,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942480,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888544,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888544,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933728,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933728,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, struct task_struct * task)
```

```json
{
  "name": "perf_event_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995264,
      "name": "perf_event_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2508",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995264,
      "name": "perf_event_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void perf_event_sched_in(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```
</details>
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

# Function: <code>task_ctx_sched_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_event_context * ctx)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403520,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2698",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403520,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476480,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2195",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476480,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540560,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2233",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540560,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571744,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2276",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571744,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639840,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2210",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639840,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768880,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2407",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768880,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836112,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2407",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836112,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932384,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932384,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986320,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986320,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581207379,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2644",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_context_sched_out",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249795,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2679",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_context_sched_out",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581276228,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2681",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_context_sched_out",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581519972,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2720",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_context_sched_out",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581867318,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2632",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_context_sched_out",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582294742,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2625",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_context_sched_out",
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
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582495510,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2625",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_context_sched_out",
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
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582663958,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2663",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_context_sched_out",
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492357776,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492357776,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226242228,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226242228,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285608032,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285608032,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272483292,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272483292,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955120,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955120,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901184,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901184,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946368,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946368,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "task_ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008240,
      "name": "task_ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2495",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008240,
      "name": "task_ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_cpu_context * cpuctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx</code> ➡️ <code>cpuctx, ctx</code>
</li>
</ul>
</details>
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
<code>enum event_type_t event_type</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, enum event_type_t event_type)
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

# Function: <code>ctx_sched_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403168,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2399",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403168,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475872,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2599",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475872,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580539968,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2663",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539968,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571264,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571264,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639312,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2658",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639312,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768336,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2902",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768336,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835568,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2897",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835568,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931808,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2915",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931808,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985744,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985744,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183088,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3169",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183088,
      "name": "ctx_sched_out",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225264,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3213",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225264,
      "name": "ctx_sched_out",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241472,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3235",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241472,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477040,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3293",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477040,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826768,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3204",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826768,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
void ctx_sched_out(struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247024,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3247",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247024,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
void ctx_sched_out(struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582447744,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3247",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447744,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
void ctx_sched_out(struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616848,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3285",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616848,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492357312,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492357312,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226241536,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226241536,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285607312,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285607312,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272482886,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272482886,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954544,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954544,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900608,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900608,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945792,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945792,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
void ctx_sched_out(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007664,
      "name": "ctx_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:3000",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:task_ctx_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007664,
      "name": "ctx_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct perf_cpu_context * cpuctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, cpuctx, event_type</code> ➡️ <code>ctx, event_type</code>
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

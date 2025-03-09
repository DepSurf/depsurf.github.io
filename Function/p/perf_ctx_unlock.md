# Function: <code>perf_ctx_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580386336,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:354",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580386336,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580452560,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:156",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452560,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514992,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:156",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514992,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546672,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:160",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546672,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627008,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:160",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627008,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580814039,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:160",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880695,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:160",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580976959,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581031085,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581186534,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:166",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581229062,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:169",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272179,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:170",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581513153,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:171",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581838931,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:171",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582265640,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:166",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582466435,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:166",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582634035,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:166",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492383176,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226205192,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226205192,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285562704,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285562704,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272466820,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272466820,
      "name": "perf_ctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580999935,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580946096,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580991133,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_ctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581052159,
      "name": "perf_ctx_unlock",
      "external": false,
      "loc": "kernel/events/core.c:159",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:event_function"
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```
</details>
</li>
</ul>

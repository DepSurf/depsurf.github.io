# Function: <code>ctx_sched_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580404672,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:2781",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404672,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580479056,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3004",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479056,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1293
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541952,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3075",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541952,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576224,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3158",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576224,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655984,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3052",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655984,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 954
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758752,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3359",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758752,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825216,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3354",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825216,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919856,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3381",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919856,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973312,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973312,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178624,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3683",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178624,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223840,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3752",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223840,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230416,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3774",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230416,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488896,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3867",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488896,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834416,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3778",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834416,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void ctx_sched_in(struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262752,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3870",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262752,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void ctx_sched_in(struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582463568,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3870",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463568,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void ctx_sched_in(struct perf_event_context * ctx, enum event_type_t event_type)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582631248,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3899",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631248,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492327184,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492327184,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226224264,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226224264,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285580496,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285580496,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272458628,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272458628,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942112,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942112,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888176,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888176,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933360,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933360,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void ctx_sched_in(struct perf_event_context * ctx, struct perf_cpu_context * cpuctx, enum event_type_t event_type, struct task_struct * task)
```

```json
{
  "name": "ctx_sched_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994896,
      "name": "ctx_sched_in",
      "external": false,
      "loc": "kernel/events/core.c:3466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994896,
      "name": "ctx_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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

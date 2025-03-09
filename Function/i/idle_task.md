# Function: <code>idle_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556144,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:3591",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "kernel/trace/ftrace.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556144,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566816,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:3844",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "kernel/trace/ftrace.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566816,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591792,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:3881",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "kernel/trace/ftrace.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591792,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576048,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:3887",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "kernel/trace/ftrace.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576048,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605744,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:3931",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "kernel/trace/ftrace.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605744,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637024,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4058",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "kernel/trace/ftrace.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637024,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674704,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4043",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674704,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706624,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4462",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706624,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748720,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748720,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784432,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4897",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784432,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774880,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:5670",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774880,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782768,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:5885",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782768,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876752,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:7048",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876752,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992640,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:7140",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992640,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580154064,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:7281",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_start_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154064,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204576,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:7382",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_start_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204576,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253136,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:7432",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:check_holdout_task",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_start_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253136,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490927336,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490927336,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224945136,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224945136,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283780416,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283780416,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271562844,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271562844,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724672,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724672,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653232,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653232,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711424,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711424,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct task_struct * idle_task(int cpu)
```

```json
{
  "name": "idle_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756352,
      "name": "idle_task",
      "external": true,
      "loc": "kernel/sched/core.c:4664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:start_graph_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756352,
      "name": "idle_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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

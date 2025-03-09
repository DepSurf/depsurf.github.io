# Function: <code>task_numa_group_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607904,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:905",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607904,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621312,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1040",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cpu",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621312,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643168,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1164",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cpu",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643168,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621872,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1161",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cpu",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621872,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653856,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1178",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cpu",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653856,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685008,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1206",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cpu",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685008,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720272,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1202",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cpu",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720272,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755760,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1253",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755760,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798080,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798080,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579841040,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1222",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841040,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833408,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1229",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833408,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842352,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1226",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842352,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946912,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1215",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "kernel/sched/debug.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946912,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060464,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1217",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060464,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230176,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1256",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230176,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293904,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1273",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293904,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580345824,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1514",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:perf_trace_sched_move_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "kernel/sched/build_utility.c:sched_show_numa",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345824,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490977504,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490977504,
      "name": "task_numa_group_id",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_numa_group_id",
      "external": false,
      "loc": "include/linux/sched/numa_balancing.h:30",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_numa_group_id",
      "external": false,
      "loc": "include/linux/sched/numa_balancing.h:30",
      "file": "fs/proc/array.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283843808,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283843808,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_numa_group_id",
      "external": false,
      "loc": "include/linux/sched/numa_balancing.h:30",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_numa_group_id",
      "external": false,
      "loc": "include/linux/sched/numa_balancing.h:30",
      "file": "fs/proc/array.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773936,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773936,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579704576,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579704576,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758448,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758448,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pid_t task_numa_group_id(struct task_struct * p)
```

```json
{
  "name": "task_numa_group_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806352,
      "name": "task_numa_group_id",
      "external": true,
      "loc": "kernel/sched/fair.c:1211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_swap_numa",
        "kernel/sched/core.c:trace_event_raw_event_sched_move_task_template",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "fs/proc/array.c:task_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806352,
      "name": "task_numa_group_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pid_t task_numa_group_id(struct task_struct * p)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pid_t task_numa_group_id(struct task_struct * p)
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

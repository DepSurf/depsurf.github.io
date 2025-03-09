# Function: <code>cpu_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 cpu_clock(int cpu)
```

```json
{
  "name": "cpu_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571280,
      "name": "cpu_clock",
      "external": true,
      "loc": "kernel/sched/clock.c:371",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571280,
      "name": "cpu_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579683059,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched.h:2468",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579707667,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched.h:2564",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579703910,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:76",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579735559,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579764252,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579807186,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825173,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:update_stats"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579728492,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579835375,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851925,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579771011,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579883695,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900453,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579803489,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579926699,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943605,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579794625,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579920571,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579931846,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579811324,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579928833,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944636,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:collect_percpu_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579908754,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052081,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071731,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:collect_percpu_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580023421,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580204666,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580179525,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397663,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:get_recent_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580248590,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:91",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580466077,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:91",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:get_recent_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
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
  "name": "cpu_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580525821,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:91",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:get_recent_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490954624,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491086012,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491101524,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:collect_percpu_times"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224986392,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 3225089900,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3225103284,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:collect_percpu_times"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283806632,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283972272,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283990268,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:collect_percpu_times"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271577930,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271674506,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271682322,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:43",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:collect_percpu_times"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579746867,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579855823,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872565,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579677251,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579790751,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807573,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579731379,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579844063,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860725,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times"
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
  "name": "cpu_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579779155,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579889103,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906101,
      "name": "cpu_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:77",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times"
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
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
u64 cpu_clock(int cpu)
```
</details>
</li>
</ul>

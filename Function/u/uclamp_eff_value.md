# Function: <code>uclamp_eff_value</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct * p, unsigned int clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690736,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:883",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690736,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579730672,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:921",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730672,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771232,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:941",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771232,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579759872,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:1100",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759872,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579767184,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:1113",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767184,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857376,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:1467",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857376,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579973296,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:1510",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973296,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580133392,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:1498",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133392,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580195760,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:1520",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195760,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
long unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243632,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:1561",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243632,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490912560,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:921",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490912560,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224926384,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:921",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224926384,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283755184,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:921",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283755184,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707328,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:921",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707328,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579635184,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:921",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635184,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_eff_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737856,
      "name": "uclamp_eff_value",
      "external": true,
      "loc": "kernel/sched/core.c:921",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util",
        "kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737856,
      "name": "uclamp_eff_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
unsigned int uclamp_eff_value(struct task_struct * p, unsigned int clamp_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int clamp_id</code> ➡️ <code>enum uclamp_id clamp_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
unsigned int uclamp_eff_value(struct task_struct * p, enum uclamp_id clamp_id)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

# Function: <code>sched_show_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558944,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:4900",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558944,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569616,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5151",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569616,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594800,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5190",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594800,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579232,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5108",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579232,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580992,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5174",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580992,
      "name": "sched_show_task",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579643402,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5299",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643402,
      "name": "sched_show_task.part.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071579643621,
      "name": "sched_show_task.cold.83",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579610256,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579680956,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5282",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680956,
      "name": "sched_show_task.part.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071579681175,
      "name": "sched_show_task.cold.83",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579648272,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579714722,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5734",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714722,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071579672288,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579757234,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757234,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071579709680,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579790617,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:6158",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790617,
      "name": "sched_show_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071579790832,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579749792,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591281970,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:6978",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281970,
      "name": "sched_show_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071591282214,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579735584,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591225054,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:7329",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591225054,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071579741920,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823135,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:8527",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592106897,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579823056,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579941533,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:8818",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593874637,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579941440,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098064,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:9002",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098064,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580156048,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:9159",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156048,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580200944,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:9146",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/update.c:check_holdout_task",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/hung_task.c:check_hung_task",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200944,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490935512,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490935512,
      "name": "sched_show_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446603336490890408,
      "name": "sched_show_task",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224954576,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224954032,
      "name": "sched_show_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 3224906300,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283729456,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283729456,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271540630,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271540630,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579733154,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733154,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071579685904,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661997,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661997,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071579614320,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717602,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717602,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071579683056,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_show_task(struct task_struct * p)
```

```json
{
  "name": "sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579764866,
      "name": "sched_show_task",
      "external": true,
      "loc": "kernel/sched/core.c:5925",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764866,
      "name": "sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071579718272,
      "name": "sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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

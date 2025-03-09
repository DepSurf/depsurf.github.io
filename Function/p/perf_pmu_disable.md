# Function: <code>perf_pmu_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580395696,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:828",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395696,
      "name": "perf_pmu_disable.part.88",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071580415216,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580464735,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1073",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464592,
      "name": "perf_pmu_disable.part.91",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071580488320,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580525823,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1081",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:group_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:group_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525344,
      "name": "perf_pmu_disable.part.92",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071580551520,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550447,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1073",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:group_sched_out",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582720,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580630687,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1112",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662448,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580767567,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1135",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767424,
      "name": "perf_pmu_disable.part.103",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580793920,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580834799,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1135",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834656,
      "name": "perf_pmu_disable.part.103",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580860416,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580931014,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930864,
      "name": "perf_pmu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580957072,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580984950,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984800,
      "name": "perf_pmu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071581009280,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581161421,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1198",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190016,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581202845,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1202",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:perf_event_context_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231648,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219645,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1200",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247376,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581457373,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1231",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483200,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581804832,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1140",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:__perf_pmu_sched_task",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828128,
      "name": "perf_pmu_disable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582233040,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1137",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:perf_ctx_disable",
        "kernel/events/core.c:perf_ctx_disable"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255392,
      "name": "perf_pmu_disable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582433872,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1137",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:perf_ctx_disable",
        "kernel/events/core.c:perf_ctx_disable"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582456000,
      "name": "perf_pmu_disable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582602256,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1148",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:perf_ctx_disable",
        "kernel/events/core.c:perf_ctx_disable"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624704,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492356056,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492356056,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226240128,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226240128,
      "name": "perf_pmu_disable",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285605616,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/core-book3s.c:power_pmu_start_txn",
        "arch/powerpc/perf/core-book3s.c:power_pmu_del",
        "arch/powerpc/perf/core-book3s.c:power_pmu_add",
        "arch/powerpc/perf/imc-pmu.c:thread_imc_pmu_start_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285605616,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272477286,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272477286,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580953750,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953600,
      "name": "perf_pmu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580978128,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580899814,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580899664,
      "name": "perf_pmu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580924256,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580944998,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580944848,
      "name": "perf_pmu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580969328,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void perf_pmu_disable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581006870,
      "name": "perf_pmu_disable",
      "external": true,
      "loc": "kernel/events/core.c:1136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_start_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006432,
      "name": "perf_pmu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071581030112,
      "name": "perf_pmu_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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

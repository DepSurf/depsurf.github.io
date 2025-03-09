# Function: <code>perf_pmu_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580395760,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:835",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580395760,
      "name": "perf_pmu_enable.part.90",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071580415264,
      "name": "perf_pmu_enable",
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580464819,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1080",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580464656,
      "name": "perf_pmu_enable.part.93",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071580488368,
      "name": "perf_pmu_enable",
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580525907,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1088",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580525408,
      "name": "perf_pmu_enable.part.94",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071580551568,
      "name": "perf_pmu_enable",
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550537,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1080",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582768,
      "name": "perf_pmu_enable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580630792,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1119",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662496,
      "name": "perf_pmu_enable",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580767669,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1142",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580767488,
      "name": "perf_pmu_enable.part.105",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580793968,
      "name": "perf_pmu_enable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580834901,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1142",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580834720,
      "name": "perf_pmu_enable.part.105",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580860464,
      "name": "perf_pmu_enable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580931119,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580930928,
      "name": "perf_pmu_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580957120,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580985055,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580984864,
      "name": "perf_pmu_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071581009328,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581161560,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1205",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190064,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581202984,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1209",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231696,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219784,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1207",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247424,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459608,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1238",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483248,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581805033,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1147",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828208,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582233273,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1144",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "kernel/events/core.c:perf_ctx_enable",
        "kernel/events/core.c:perf_ctx_enable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255488,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582434681,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1144",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "kernel/events/core.c:perf_ctx_enable",
        "kernel/events/core.c:perf_ctx_enable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582456096,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582602953,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1155",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
        "kernel/events/core.c:perf_ctx_enable",
        "kernel/events/core.c:perf_ctx_enable"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_commit_txn",
        "arch/x86/events/intel/core.c:intel_pmu_read_event",
        "arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624800,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492356152,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
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
      "addr": 18446603336492356152,
      "name": "perf_pmu_enable",
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226240224,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226240224,
      "name": "perf_pmu_enable",
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285605760,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/core-book3s.c:power_pmu_commit_txn",
        "arch/powerpc/perf/core-book3s.c:power_pmu_cancel_txn",
        "arch/powerpc/perf/core-book3s.c:power_pmu_cancel_txn",
        "arch/powerpc/perf/core-book3s.c:power_pmu_del",
        "arch/powerpc/perf/core-book3s.c:power_pmu_add",
        "arch/powerpc/perf/imc-pmu.c:thread_imc_pmu_commit_txn",
        "arch/powerpc/perf/imc-pmu.c:thread_imc_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285605760,
      "name": "perf_pmu_enable",
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272477404,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_cgroup_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272477404,
      "name": "perf_pmu_enable",
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580953855,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580953664,
      "name": "perf_pmu_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580978176,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580899919,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580899728,
      "name": "perf_pmu_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580924304,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945103,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071580944912,
      "name": "perf_pmu_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580969376,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void perf_pmu_enable(struct pmu * pmu)
```

```json
{
  "name": "perf_pmu_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581006975,
      "name": "perf_pmu_enable",
      "external": true,
      "loc": "kernel/events/core.c:1143",
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
        "arch/x86/events/core.c:x86_pmu_commit_txn",
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
      "addr": 18446744071581006496,
      "name": "perf_pmu_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071581030160,
      "name": "perf_pmu_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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

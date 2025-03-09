# Function: <code>task_curr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579519367,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1000",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:task_function_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544976,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533479,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:918",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556304,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557955,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:925",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581136,
      "name": "task_curr",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544307,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:846",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564592,
      "name": "task_curr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579572215,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:856",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594240,
      "name": "task_curr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579600807,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:834",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625824,
      "name": "task_curr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579637959,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:829",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663360,
      "name": "task_curr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662789,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1272",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692912,
      "name": "task_curr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699877,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733296,
      "name": "task_curr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579740357,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1468",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771920,
      "name": "task_curr",
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579724693,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1679",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760624,
      "name": "task_curr",
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579732085,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1687",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768288,
      "name": "task_curr",
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812126,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:2065",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858672,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579928261,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:2161",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:check_slow_task",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973872,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580079717,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:2149",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_check_slow_task",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:check_slow_task",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/freezer.c:__set_task_frozen",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134048,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163637,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:2176",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_check_slow_task",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:check_slow_task",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/freezer.c:__set_task_frozen",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196352,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580213109,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:2214",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/update.c:trc_check_slow_task",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/tree.c:check_slow_task",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/freezer.c:__set_task_frozen",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244224,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490896020,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490913680,
      "name": "task_curr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224904464,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224929036,
      "name": "task_curr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283725408,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283758608,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271538302,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271551780,
      "name": "task_curr",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676197,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709952,
      "name": "task_curr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579604517,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637808,
      "name": "task_curr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579673413,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699424,
      "name": "task_curr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int task_curr(const struct task_struct * p)
```

```json
{
  "name": "task_curr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713056,
      "name": "task_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process"
      ],
      "caller_func": [
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/rcu/tree.c:rcu_request_urgent_qs_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740544,
      "name": "task_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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

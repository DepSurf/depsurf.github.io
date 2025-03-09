# Function: <code>sched_setscheduler_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579541904,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4079",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541904,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579556207,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4329",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553296,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581039,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4366",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578016,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579570143,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4266",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561408,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579599903,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4310",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590656,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631391,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4445",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622656,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669135,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4430",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659952,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579700831,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4867",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685888,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579741711,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725360,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579778200,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5315",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768816,
      "name": "sched_setscheduler_nocheck",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579768552,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:6090",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775136,
      "name": "sched_setscheduler_nocheck",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579776248,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:6391",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783744,
      "name": "sched_setscheduler_nocheck",
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851238,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7555",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877888,
      "name": "sched_setscheduler_nocheck",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579968806,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7663",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993984,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580128694,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7805",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155504,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580190758,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7914",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/trace/trace_osnoise.c:timerlat_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205888,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580237894,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7975",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:kthread",
        "kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/trace/trace_osnoise.c:timerlat_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254208,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490920472,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490907192,
      "name": "sched_setscheduler_nocheck",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224937564,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_thread",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224921412,
      "name": "sched_setscheduler_nocheck",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283770556,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283748048,
      "name": "sched_setscheduler_nocheck",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271557090,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271547612,
      "name": "sched_setscheduler_nocheck",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579718335,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702272,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646223,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629424,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579705599,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694272,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int sched_setscheduler_nocheck(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749263,
      "name": "sched_setscheduler_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732704,
      "name": "sched_setscheduler_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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

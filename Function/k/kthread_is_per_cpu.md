# Function: <code>kthread_is_per_cpu</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct * k)
```

```json
{
  "name": "kthread_is_per_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681280,
      "name": "kthread_is_per_cpu",
      "external": true,
      "loc": "kernel/kthread.c:529",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:select_fallback_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681280,
      "name": "kthread_is_per_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
bool kthread_is_per_cpu(struct task_struct * p)
```

```json
{
  "name": "kthread_is_per_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688160,
      "name": "kthread_is_per_cpu",
      "external": true,
      "loc": "kernel/kthread.c:556",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:is_cpu_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688160,
      "name": "kthread_is_per_cpu",
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
bool kthread_is_per_cpu(struct task_struct * p)
```

```json
{
  "name": "kthread_is_per_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766576,
      "name": "kthread_is_per_cpu",
      "external": true,
      "loc": "kernel/kthread.c:556",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:select_fallback_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766576,
      "name": "kthread_is_per_cpu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct * p)
```

```json
{
  "name": "kthread_is_per_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874048,
      "name": "kthread_is_per_cpu",
      "external": true,
      "loc": "kernel/kthread.c:616",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/fair.c:can_migrate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874048,
      "name": "kthread_is_per_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool kthread_is_per_cpu(struct task_struct * p)
```

```json
{
  "name": "kthread_is_per_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017184,
      "name": "kthread_is_per_cpu",
      "external": true,
      "loc": "kernel/kthread.c:616",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017184,
      "name": "kthread_is_per_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool kthread_is_per_cpu(struct task_struct * p)
```

```json
{
  "name": "kthread_is_per_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071040,
      "name": "kthread_is_per_cpu",
      "external": true,
      "loc": "kernel/kthread.c:617",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071040,
      "name": "kthread_is_per_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool kthread_is_per_cpu(struct task_struct * p)
```

```json
{
  "name": "kthread_is_per_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113872,
      "name": "kthread_is_per_cpu",
      "external": true,
      "loc": "kernel/kthread.c:616",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113872,
      "name": "kthread_is_per_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool kthread_is_per_cpu(struct task_struct * k)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * k</code>
</li>
</ul>
</details>
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

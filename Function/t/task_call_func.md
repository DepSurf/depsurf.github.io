# Function: <code>task_call_func</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int task_call_func(struct task_struct * p, task_call_f func, void * arg)
```

```json
{
  "name": "task_call_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986608,
      "name": "task_call_func",
      "external": true,
      "loc": "kernel/sched/core.c:4229",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/tree.c:rcu_print_task_stall",
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986608,
      "name": "task_call_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int task_call_func(struct task_struct * p, task_call_f func, void * arg)
```

```json
{
  "name": "task_call_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147712,
      "name": "task_call_func",
      "external": true,
      "loc": "kernel/sched/core.c:4327",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/tree.c:rcu_print_task_stall",
        "kernel/livepatch/transition.c:klp_try_switch_task",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147712,
      "name": "task_call_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int task_call_func(struct task_struct * p, task_call_f func, void * arg)
```

```json
{
  "name": "task_call_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199712,
      "name": "task_call_func",
      "external": true,
      "loc": "kernel/sched/core.c:4404",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/tree.c:rcu_print_task_stall",
        "kernel/livepatch/transition.c:klp_try_switch_task",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199712,
      "name": "task_call_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int task_call_func(struct task_struct * p, task_call_f func, void * arg)
```

```json
{
  "name": "task_call_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580247840,
      "name": "task_call_func",
      "external": true,
      "loc": "kernel/sched/core.c:4426",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/tree.c:rcu_print_task_stall",
        "kernel/livepatch/transition.c:klp_try_switch_task",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247840,
      "name": "task_call_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int task_call_func(struct task_struct * p, task_call_f func, void * arg)
```
</details>
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

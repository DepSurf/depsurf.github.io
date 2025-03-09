# Function: <code>task_rcu_dereference</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```

```json
{
  "name": "task_rcu_dereference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395808,
      "name": "task_rcu_dereference",
      "external": true,
      "loc": "kernel/exit.c:217",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:try_get_task_struct",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395808,
      "name": "task_rcu_dereference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```

```json
{
  "name": "task_rcu_dereference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416144,
      "name": "task_rcu_dereference",
      "external": true,
      "loc": "kernel/exit.c:226",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:try_get_task_struct",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416144,
      "name": "task_rcu_dereference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```

```json
{
  "name": "task_rcu_dereference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404240,
      "name": "task_rcu_dereference",
      "external": true,
      "loc": "kernel/exit.c:233",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404240,
      "name": "task_rcu_dereference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```

```json
{
  "name": "task_rcu_dereference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432192,
      "name": "task_rcu_dereference",
      "external": true,
      "loc": "kernel/exit.c:233",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_find_cpu",
        "kernel/sched/membarrier.c:SyS_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432192,
      "name": "task_rcu_dereference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```

```json
{
  "name": "task_rcu_dereference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447440,
      "name": "task_rcu_dereference",
      "external": true,
      "loc": "kernel/exit.c:233",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_find_cpu",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447440,
      "name": "task_rcu_dereference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```

```json
{
  "name": "task_rcu_dereference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480896,
      "name": "task_rcu_dereference",
      "external": true,
      "loc": "kernel/exit.c:234",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_find_cpu",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480896,
      "name": "task_rcu_dereference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```

```json
{
  "name": "task_rcu_dereference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498896,
      "name": "task_rcu_dereference",
      "external": true,
      "loc": "kernel/exit.c:236",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_find_cpu",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498896,
      "name": "task_rcu_dereference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```
</details>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
struct task_struct * task_rcu_dereference(struct task_struct * * ptask)
```
</details>
</li>
</ul>

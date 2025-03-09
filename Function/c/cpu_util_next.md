# Function: <code>cpu_util_next</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687712,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6384",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:compute_energy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687712,
      "name": "cpu_util_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6250",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797504,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6421",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797504,
      "name": "cpu_util_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788304,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6491",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788304,
      "name": "cpu_util_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579796464,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6576",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796464,
      "name": "cpu_util_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892288,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6652",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892288,
      "name": "cpu_util_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004448,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6575",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004448,
      "name": "cpu_util_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166912,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6953",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166912,
      "name": "cpu_util_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "cpu_util_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_util_next",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
long unsigned int cpu_util_next(int cpu, struct task_struct * p, int dst_cpu)
```
</details>
</li>
</ul>

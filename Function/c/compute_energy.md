# Function: <code>compute_energy</code>

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
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688624,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6426",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688624,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6292",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799104,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6463",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799104,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790288,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6533",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790288,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801856,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6618",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801856,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898272,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6694",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898272,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010704,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6663",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010704,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
long unsigned int compute_energy(struct energy_env * eenv, struct perf_domain * pd, struct cpumask * pd_cpus, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580181149,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:7145",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173968,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
long unsigned int compute_energy(struct energy_env * eenv, struct perf_domain * pd, struct cpumask * pd_cpus, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238064,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:7473",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238064,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
long unsigned int compute_energy(struct energy_env * eenv, struct perf_domain * pd, struct cpumask * pd_cpus, struct task_struct * p, int dst_cpu)
```

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288880,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:7884",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288880,
      "name": "compute_energy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
  "name": "compute_energy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "compute_energy",
      "external": false,
      "loc": "kernel/sched/fair.c:6253",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int compute_energy(struct task_struct * p, int dst_cpu, struct perf_domain * pd)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct energy_env * eenv</code>
</li>
<li>
<b>Param added. </b>
<code>struct cpumask * pd_cpus</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, dst_cpu, pd</code> ➡️ <code>eenv, pd, pd_cpus, p, dst_cpu</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

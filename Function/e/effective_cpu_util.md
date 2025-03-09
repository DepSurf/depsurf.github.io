# Function: <code>effective_cpu_util</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum cpu_util_type type, struct task_struct * p)
```

```json
{
  "name": "effective_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579783485,
      "name": "effective_cpu_util",
      "external": true,
      "loc": "kernel/sched/core.c:5911",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": [
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782816,
      "name": "effective_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum cpu_util_type type, struct task_struct * p)
```

```json
{
  "name": "effective_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877571,
      "name": "effective_cpu_util",
      "external": true,
      "loc": "kernel/sched/core.c:7074",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": [
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876832,
      "name": "effective_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum cpu_util_type type, struct task_struct * p)
```

```json
{
  "name": "effective_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579993572,
      "name": "effective_cpu_util",
      "external": true,
      "loc": "kernel/sched/core.c:7166",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": [
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/build_utility.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992720,
      "name": "effective_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, enum cpu_util_type type, struct task_struct * p)
```

```json
{
  "name": "effective_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580155088,
      "name": "effective_cpu_util",
      "external": true,
      "loc": "kernel/sched/core.c:7307",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/build_utility.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154160,
      "name": "effective_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, enum cpu_util_type type, struct task_struct * p)
```

```json
{
  "name": "effective_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580205505,
      "name": "effective_cpu_util",
      "external": true,
      "loc": "kernel/sched/core.c:7408",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/build_utility.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204672,
      "name": "effective_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int * min, long unsigned int * max)
```

```json
{
  "name": "effective_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580253825,
      "name": "effective_cpu_util",
      "external": true,
      "loc": "kernel/sched/core.c:7471",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/build_utility.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253520,
      "name": "effective_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum cpu_util_type type, struct task_struct * p)
```
</details>
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
<b>Param removed. </b>
<code>long unsigned int max</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, util_cfs, max, type, p</code> ➡️ <code>cpu, util_cfs, type, p</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int * min</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int * max</code>
</li>
<li>
<b>Param removed. </b>
<code>enum cpu_util_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * p</code>
</li>
</ul>
</details>
</li>
</ul>

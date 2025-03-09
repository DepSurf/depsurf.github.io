# Function: <code>cpu_util_cfs</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579775760,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2185",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579820971,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2250",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579849064,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2356",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579897320,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579940344,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2472",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579927773,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2595",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579783457,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2646",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933837,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2646",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579877546,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2953",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580057695,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2953",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579993461,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2899",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044265,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2899",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580179716,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2899",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/sched/build_utility.c:sugov_get_util"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580154981,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2990",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_util"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580208379,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2990",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sg_wakeup_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580364468,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2990",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/sched/build_utility.c:sugov_get_util"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int cpu_util_cfs(int cpu)
```

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580266909,
      "name": "cpu_util_cfs",
      "external": true,
      "loc": "kernel/sched/fair.c:7329",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_util",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302112,
      "name": "cpu_util_cfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
long unsigned int cpu_util_cfs(int cpu)
```

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580337123,
      "name": "cpu_util_cfs",
      "external": true,
      "loc": "kernel/sched/fair.c:7724",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_util",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354768,
      "name": "cpu_util_cfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491095740,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225099272,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283984900,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579869432,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579804376,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579857592,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
  "name": "cpu_util_cfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579902872,
      "name": "cpu_util_cfs",
      "external": false,
      "loc": "kernel/sched/sched.h:2399",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ],
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
long unsigned int cpu_util_cfs(int cpu)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

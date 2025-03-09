# Function: <code>dl_bw_of</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dl_bw * dl_bw_of(int i)
```

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579540373,
      "name": "dl_bw_of",
      "external": true,
      "loc": "kernel/sched/core.c:2283",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_rt_handler"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:task_dead_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552992,
      "name": "dl_bw_of",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dl_bw * dl_bw_of(int i)
```

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579485,
      "name": "dl_bw_of",
      "external": true,
      "loc": "kernel/sched/core.c:2462",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:task_dead_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563808,
      "name": "dl_bw_of",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dl_bw * dl_bw_of(int i)
```

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605677,
      "name": "dl_bw_of",
      "external": true,
      "loc": "kernel/sched/core.c:2472",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:task_dead_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588704,
      "name": "dl_bw_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579669302,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:48",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699750,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:49",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579733830,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:46",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579773510,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579800914,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579848754,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579887442,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579881638,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:69",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579890758,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:69",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580005446,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:69",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580135649,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:99",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580310145,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:101",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580340388,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:103",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580392164,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:116",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491038912,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225048620,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283917956,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271640036,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579821106,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579755714,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579809122,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
  "name": "dl_bw_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579854249,
      "name": "dl_bw_of",
      "external": false,
      "loc": "kernel/sched/deadline.c:47",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct dl_bw * dl_bw_of(int i)
```
</details>
</li>
</ul>

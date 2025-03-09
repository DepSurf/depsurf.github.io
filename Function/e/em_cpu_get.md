# Function: <code>em_cpu_get</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010496,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:179",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010496,
      "name": "em_cpu_get",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579990159,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:246",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988368,
      "name": "em_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991895,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:246",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline",
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990208,
      "name": "em_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580123831,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:241",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline",
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122144,
      "name": "em_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580264762,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:305",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263040,
      "name": "em_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580471204,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:302",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468640,
      "name": "em_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580542787,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:302",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540096,
      "name": "em_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct em_perf_domain * em_cpu_get(int cpu)
```

```json
{
  "name": "em_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580604675,
      "name": "em_cpu_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:302",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601904,
      "name": "em_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct em_perf_domain * em_cpu_get(int cpu)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

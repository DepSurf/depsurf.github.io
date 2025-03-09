# Function: <code>intel_pstate_get_hwp_max</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586627501,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:796",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits"
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
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587110429,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:687",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587408432,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:711",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408432,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587587648,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:751",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587587648,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587863824,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:751",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587863824,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588068608,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:752",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588068608,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588928912,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:758",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_cpu_pstates",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928912,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588949744,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:822",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587690752,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:752",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690752,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587466880,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:752",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466880,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588024752,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:752",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024752,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```

```json
{
  "name": "intel_pstate_get_hwp_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588140224,
      "name": "intel_pstate_get_hwp_max",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:752",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140224,
      "name": "intel_pstate_get_hwp_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int * phy_max, int * current_max)
```
</details>
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

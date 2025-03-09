# Function: <code>intel_pstate_get_hwp_cap</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_get_hwp_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588837873,
      "name": "intel_pstate_get_hwp_cap",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:832",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_get_hwp_cap(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_get_hwp_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589527456,
      "name": "intel_pstate_get_hwp_cap",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:908",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589527456,
      "name": "intel_pstate_get_hwp_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void intel_pstate_get_hwp_cap(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_get_hwp_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591017392,
      "name": "intel_pstate_get_hwp_cap",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:931",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591017392,
      "name": "intel_pstate_get_hwp_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void intel_pstate_get_hwp_cap(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_get_hwp_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592727856,
      "name": "intel_pstate_get_hwp_cap",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:906",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592727856,
      "name": "intel_pstate_get_hwp_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void intel_pstate_get_hwp_cap(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_get_hwp_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593165008,
      "name": "intel_pstate_get_hwp_cap",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:926",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593165008,
      "name": "intel_pstate_get_hwp_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void intel_pstate_get_hwp_cap(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_get_hwp_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593918128,
      "name": "intel_pstate_get_hwp_cap",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:950",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593918128,
      "name": "intel_pstate_get_hwp_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void intel_pstate_get_hwp_cap(struct cpudata * cpu)
```
</details>
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

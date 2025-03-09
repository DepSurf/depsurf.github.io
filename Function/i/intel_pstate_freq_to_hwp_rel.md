# Function: <code>intel_pstate_freq_to_hwp_rel</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int intel_pstate_freq_to_hwp_rel(struct cpudata * cpu, int freq, unsigned int relation)
```

```json
{
  "name": "intel_pstate_freq_to_hwp_rel",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593930777,
      "name": "intel_pstate_freq_to_hwp_rel",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:532",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593917696,
      "name": "intel_pstate_freq_to_hwp_rel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int intel_pstate_freq_to_hwp_rel(struct cpudata * cpu, int freq, unsigned int relation)
```
</details>
</li>
</ul>

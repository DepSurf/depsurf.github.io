# Function: <code>intel_cpufreq_hwp_update</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata * cpu, u32 min, u32 max, u32 desired, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_hwp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588835024,
      "name": "intel_cpufreq_hwp_update",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2509",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835024,
      "name": "intel_cpufreq_hwp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void intel_cpufreq_hwp_update(struct cpudata * cpu, u32 min, u32 max, u32 desired, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_hwp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589530416,
      "name": "intel_cpufreq_hwp_update",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2680",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589530416,
      "name": "intel_cpufreq_hwp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void intel_cpufreq_hwp_update(struct cpudata * cpu, u32 min, u32 max, u32 desired, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_hwp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591021440,
      "name": "intel_cpufreq_hwp_update",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2846",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591021440,
      "name": "intel_cpufreq_hwp_update",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata * cpu, u32 min, u32 max, u32 desired, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_hwp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592732336,
      "name": "intel_cpufreq_hwp_update",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2810",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592732336,
      "name": "intel_cpufreq_hwp_update",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata * cpu, u32 min, u32 max, u32 desired, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_hwp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593169456,
      "name": "intel_cpufreq_hwp_update",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2836",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593169456,
      "name": "intel_cpufreq_hwp_update",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata * cpu, u32 min, u32 max, u32 desired, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_hwp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593924688,
      "name": "intel_cpufreq_hwp_update",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2860",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593924688,
      "name": "intel_cpufreq_hwp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void intel_cpufreq_hwp_update(struct cpudata * cpu, u32 min, u32 max, u32 desired, bool fast_switch)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

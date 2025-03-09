# Function: <code>amd_pstate_update</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void amd_pstate_update(struct amd_cpudata * cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch)
```

```json
{
  "name": "amd_pstate_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590999136,
      "name": "amd_pstate_update",
      "external": false,
      "loc": "drivers/cpufreq/amd-pstate.c:266",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590999136,
      "name": "amd_pstate_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void amd_pstate_update(struct amd_cpudata * cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch)
```

```json
{
  "name": "amd_pstate_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592706784,
      "name": "amd_pstate_update",
      "external": false,
      "loc": "drivers/cpufreq/amd-pstate.c:214",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592706784,
      "name": "amd_pstate_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void amd_pstate_update(struct amd_cpudata * cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch, int gov_flags)
```

```json
{
  "name": "amd_pstate_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593141984,
      "name": "amd_pstate_update",
      "external": false,
      "loc": "drivers/cpufreq/amd-pstate.c:429",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593141984,
      "name": "amd_pstate_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
void amd_pstate_update(struct amd_cpudata * cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch, int gov_flags)
```

```json
{
  "name": "amd_pstate_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593895856,
      "name": "amd_pstate_update",
      "external": false,
      "loc": "drivers/cpufreq/amd-pstate.c:430",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593895856,
      "name": "amd_pstate_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void amd_pstate_update(struct amd_cpudata * cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int gov_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

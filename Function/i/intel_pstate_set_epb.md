# Function: <code>intel_pstate_set_epb</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586503280,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:682",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586503280,
      "name": "intel_pstate_set_epb",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586629920,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:622",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629920,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587112464,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:513",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112464,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587411104,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:537",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411104,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587591216,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:560",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587591216,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587865312,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:560",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865312,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588070112,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:561",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070112,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588932016,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:561",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588932016,
      "name": "intel_pstate_set_epb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588940448,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:552",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940448,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588828944,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:552",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588828944,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589524288,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:625",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589524288,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591013920,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:638",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591013920,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592724128,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:613",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592724128,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593161328,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:631",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593161328,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593914736,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:655",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593914736,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587692256,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:561",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692256,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468384,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:561",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468384,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026256,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:561",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026256,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int intel_pstate_set_epb(int cpu, s16 pref)
```

```json
{
  "name": "intel_pstate_set_epb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588141728,
      "name": "intel_pstate_set_epb",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:561",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588141728,
      "name": "intel_pstate_set_epb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref)
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

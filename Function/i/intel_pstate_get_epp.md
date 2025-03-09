# Function: <code>intel_pstate_get_epp</code>

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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586504336,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:658",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586504336,
      "name": "intel_pstate_get_epp",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586629552,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:598",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629552,
      "name": "intel_pstate_get_epp",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587112096,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:489",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112096,
      "name": "intel_pstate_get_epp",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587410640,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:513",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410640,
      "name": "intel_pstate_get_epp",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587590752,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:536",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587590752,
      "name": "intel_pstate_get_epp",
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867488,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:536",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867488,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588072720,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:537",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588072720,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588929584,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:537",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588929584,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588940288,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:528",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940288,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588828784,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:528",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588828784,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589524128,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:601",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589524128,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591013744,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:614",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591013744,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592722608,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:589",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592722608,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593159696,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:607",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593159696,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593913616,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:631",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593913616,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587694864,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:537",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587694864,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587470992,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:537",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470992,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588028864,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:537",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028864,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```

```json
{
  "name": "intel_pstate_get_epp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588144336,
      "name": "intel_pstate_get_epp",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:537",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144336,
      "name": "intel_pstate_get_epp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
s16 intel_pstate_get_epp(struct cpudata * cpu_data, u64 hwp_req_data)
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

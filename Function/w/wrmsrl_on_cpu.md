# Function: <code>wrmsrl_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151472,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:81",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:core_set_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151472,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446832,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:81",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_min_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446832,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574480,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:81",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574480,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613376,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:81",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613376,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859376,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:82",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859376,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059840,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059840,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143968,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143968,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334096,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334096,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468768,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468768,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585032512,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032512,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585184400,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184400,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066352,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066352,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585513088,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513088,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663616,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663616,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587911616,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911616,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588185568,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_offline",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_reenable",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_set_epp",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185568,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477568,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_offline",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_reenable",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_set_epp",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477568,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584437520,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437520,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372544,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372544,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584420432,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420432,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```

```json
{
  "name": "wrmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526480,
      "name": "wrmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:83",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526480,
      "name": "wrmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q)
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

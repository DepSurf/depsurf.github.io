# Function: <code>rdmsrl_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151232,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:50",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151232,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446592,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:50",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446592,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574240,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:50",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574240,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613136,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:50",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613136,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859136,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:51",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859136,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059600,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059600,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143728,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143728,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333856,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333856,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468528,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468528,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585032272,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032272,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585184160,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184160,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066112,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066112,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585512848,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585512848,
      "name": "rdmsrl_on_cpu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663344,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663344,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587911312,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911312,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588185264,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185264,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477264,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477264,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584437280,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437280,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372304,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372304,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584420192,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420192,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```

```json
{
  "name": "rdmsrl_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526240,
      "name": "rdmsrl_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:52",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max",
        "drivers/cpufreq/intel_pstate.c:show_base_frequency",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526240,
      "name": "rdmsrl_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 * q)
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

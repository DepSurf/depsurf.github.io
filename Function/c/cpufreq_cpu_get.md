# Function: <code>cpufreq_cpu_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585852096,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:276",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stat_notifier_trans",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852096,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586251552,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:230",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251552,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586456384,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:230",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586456384,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586580960,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:230",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586580960,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587064240,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:236",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064240,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587362368,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:220",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587362368,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587542240,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:220",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587542240,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:210",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832706,
      "name": "cpufreq_cpu_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587816832,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588022032,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022032,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588889296,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588889296,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588900752,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900752,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588789312,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:215",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588789312,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589482160,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:215",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482160,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590955552,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:216",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590955552,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592658128,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:216",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592658128,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593088864,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:221",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593088864,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593841232,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:222",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_is_eas_possible",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593841232,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501297024,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501297024,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233775336,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233775336,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294811232,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294811232,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647024,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647024,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420896,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420896,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587978176,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978176,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093552,
      "name": "cpufreq_cpu_get",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:213",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093552,
      "name": "cpufreq_cpu_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get(unsigned int cpu)
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

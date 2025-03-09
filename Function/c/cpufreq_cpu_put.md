# Function: <code>cpufreq_cpu_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585852256,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:308",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stat_notifier_trans",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate",
        "drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852256,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586264478,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:262",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251712,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586468778,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:262",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586456544,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586593498,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:262",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586581120,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587076810,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:268",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064400,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587374512,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:252",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587362512,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587554448,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:252",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587542384,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587819105,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:238",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816944,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588023345,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022160,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588896083,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:246",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588881936,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588908023,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:246",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894752,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588796023,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:243",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588783760,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589488388,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:243",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589476016,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590970290,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:244",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590955696,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592674583,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:244",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592658288,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593105414,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:249",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593089024,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593858166,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:250",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_is_eas_possible",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq",
        "drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593841392,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501297488,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501285224,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233776848,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233775568,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294813488,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294811504,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587648337,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647152,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587422209,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587421024,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587979489,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978304,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588094865,
      "name": "cpufreq_cpu_put",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_get_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_release"
      ],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093680,
      "name": "cpufreq_cpu_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void cpufreq_cpu_put(struct cpufreq_policy * policy)
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

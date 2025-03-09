# Function: <code>get_cpu_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584409536,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:382",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409536,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584744965,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:382",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744896,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584934981,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:383",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584934912,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585019573,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:385",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585019504,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585441893,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:395",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441824,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585685648,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585685648,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585815856,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815856,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586049552,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049552,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586197600,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586197600,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586961269,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:393",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_init",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961024,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587046629,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:391",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_create_pd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_init",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587046384,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586930437,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:391",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_create_pd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586930192,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587492901,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:391",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_create_pd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587492624,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588816117,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:391",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_create_pd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814576,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590314837,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:391",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_create_pd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590313056,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590634677,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:391",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_create_pd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590633536,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590994245,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:420",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/cpu.c:cpu_is_hotpluggable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/energy_model.c:em_dev_register_perf_domain",
        "kernel/power/energy_model.c:em_create_pd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/pmdomain/core.c:genpd_add_device",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590993008,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498998768,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpuinfo.c:cpuid_cpu_offline",
        "arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/arch_topology.c:register_cpu_capacity_sysctl",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498998768,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231565816,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/cpuidle.c:arm_cpuidle_init",
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus",
        "arch/arm/common/bL_switcher.c:bL_switcher_restore_cpus",
        "arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain",
        "arch/arm/mach-vexpress/spc.c:ve_spc_clk_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_probe",
        "drivers/soc/qcom/spm.c:spm_dev_probe",
        "drivers/soc/qcom/spm.c:qcom_cpuidle_init",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/arch_topology.c:register_cpu_capacity_sysctl",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/opp/ti-opp-supply.c:ti_opp_supply_probe",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe",
        "drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231565816,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292156928,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr_group",
        "arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr",
        "arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr_group",
        "arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr",
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online",
        "arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_readd",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292156928,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276371546,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves",
        "arch/riscv/kernel/cacheinfo.c:_init_cache_level",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/arch_topology.c:register_cpu_capacity_sysctl",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276371546,
      "name": "get_cpu_device",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585957808,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585957808,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585807072,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807072,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586147616,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147616,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct device * get_cpu_device(unsigned int cpu)
```

```json
{
  "name": "get_cpu_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586256320,
      "name": "get_cpu_device",
      "external": true,
      "loc": "drivers/base/cpu.c:398",
      "file": "drivers/base/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_online",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/cpu.c:cpu_is_hotpluggable",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpuidle/governor.c:cpuidle_governor_latency_req",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586256320,
      "name": "get_cpu_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

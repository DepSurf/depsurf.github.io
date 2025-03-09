# Function: <code>__cpuhp_remove_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386192,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1546",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386192,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407536,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1581",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:trace_init",
        "kernel/padata.c:padata_driver_exit",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407536,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395760,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1576",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_exit",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395760,
      "name": "__cpuhp_remove_state",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423504,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1764",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_exit",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423504,
      "name": "__cpuhp_remove_state",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438208,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1846",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_exit",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438208,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471168,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1868",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_exit",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471168,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488960,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1894",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488960,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514896,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514896,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543728,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2040",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543728,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525440,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2051",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525440,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529104,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2154",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529104,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601200,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2185",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601200,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693552,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2207",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693552,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817568,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2231",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817568,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865584,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2616",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zswap.c:zswap_setup",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_unregister",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory",
        "drivers/net/virtio_net.c:virtio_net_driver_exit",
        "drivers/net/virtio_net.c:virtio_net_driver_exit",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865584,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903488,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:2662",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_unregister",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory",
        "drivers/net/virtio_net.c:virtio_net_driver_exit",
        "drivers/net/virtio_net.c:virtio_net_driver_exit",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903488,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490651696,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_exit",
        "virt/kvm/kvm_main.c:kvm_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/firmware/arm_sdei.c:sdei_reboot_notifier",
        "drivers/firmware/arm_sdei.c:sdei_device_freeze",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_exit",
        "drivers/perf/arm-ccn.c:arm_ccn_init",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_exit",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_init",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_exit",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_init",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_exit",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490651696,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224728156,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init",
        "arch/arm/common/bL_switcher.c:bL_switcher_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_init",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_exit",
        "drivers/perf/arm-ccn.c:arm_ccn_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224728156,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283473536,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283473536,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271399972,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271399972,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488560,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488560,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417440,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/hv/vmbus_drv.c:vmbus_exit",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "drivers/hv/vmbus_drv.c:hv_kexec_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417440,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488480,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488480,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```

```json
{
  "name": "__cpuhp_remove_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520784,
      "name": "__cpuhp_remove_state",
      "external": true,
      "loc": "kernel/cpu.c:1909",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_exit",
        "kernel/padata.c:padata_driver_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520784,
      "name": "__cpuhp_remove_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke)
```
</details>
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

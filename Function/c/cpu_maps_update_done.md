# Function: <code>cpu_maps_update_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579373824,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:46",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpu_hotplug_disable",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:register_cpu_notifier",
        "kernel/cpu.c:unregister_cpu_notifier",
        "kernel/cpu.c:cpu_down",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/rapl.c:rapl_pmu_init",
        "arch/x86/events/intel/rapl.c:rapl_pmu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/events/core.c:perf_event_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/zswap.c:__zswap_pool_release",
        "mm/zswap.c:zswap_pool_create",
        "mm/zswap.c:zswap_pool_create",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_unregister_cpu_notifier",
        "drivers/idle/intel_idle.c:intel_idle_exit",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_init",
        "net/core/flow.c:flow_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373824,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579389632,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:123",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:unregister_cpu_notifier",
        "kernel/cpu.c:register_cpu_notifier",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "mm/vmstat.c:setup_vmstat",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:__zswap_pool_release",
        "mm/zswap.c:zswap_pool_create",
        "mm/zswap.c:zswap_pool_create",
        "mm/zsmalloc.c:zs_unregister_cpu_notifier",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_init",
        "net/core/flow.c:flow_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383312,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410029,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:192",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407840,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579397421,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:201",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396336,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579425485,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:276",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424416,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439267,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:273",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439664,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472940,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:271",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471568,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491912,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:272",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489360,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517848,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515296,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545119,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:276",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544176,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526831,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:276",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525888,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531039,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:281",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529824,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603298,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:292",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602000,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579695848,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:293",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694480,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819772,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:293",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818304,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579869134,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:472",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867632,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579907054,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:472",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:cpu_hotplug_pm_callback",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905536,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490655228,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490652304,
      "name": "cpu_maps_update_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224731728,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_up",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224729004,
      "name": "cpu_maps_update_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283478192,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283474416,
      "name": "cpu_maps_update_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271400714,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpu_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271400392,
      "name": "cpu_maps_update_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491512,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488960,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420376,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417824,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491432,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488880,
      "name": "cpu_maps_update_done",
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
void cpu_maps_update_done()
```

```json
{
  "name": "cpu_maps_update_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579523928,
      "name": "cpu_maps_update_done",
      "external": true,
      "loc": "kernel/cpu.c:275",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down",
        "kernel/cpu.c:cpu_hotplug_enable",
        "kernel/cpu.c:cpu_hotplug_disable"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521264,
      "name": "cpu_maps_update_done",
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

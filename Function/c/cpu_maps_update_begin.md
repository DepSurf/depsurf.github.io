# Function: <code>cpu_maps_update_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579373792,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:40",
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
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/rapl.c:rapl_pmu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/events/core.c:perf_event_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/zswap.c:__zswap_pool_release",
        "mm/zswap.c:zswap_pool_create",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_unregister_cpu_notifier",
        "drivers/idle/intel_idle.c:intel_idle_exit",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373792,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579389574,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:117",
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
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "mm/vmstat.c:setup_vmstat",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:__zswap_pool_release",
        "mm/zswap.c:zswap_pool_create",
        "mm/zsmalloc.c:zs_unregister_cpu_notifier",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383280,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579409974,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:187",
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
      "addr": 18446744071579407808,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579397366,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:196",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396304,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579425430,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:271",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424384,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439135,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:268",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439632,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472815,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:266",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471536,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491749,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:267",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489328,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517685,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515264,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545082,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:271",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544144,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526794,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:271",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525856,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531002,
      "name": "cpu_maps_update_begin",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529792,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603261,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:287",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601968,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579695798,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:288",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694448,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819720,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:288",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818256,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579869101,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:467",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867584,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579907021,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:467",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905488,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490655180,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490652264,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224731692,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
      "addr": 3224728968,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283478132,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
      "addr": 13835058055283474352,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271400534,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
      "addr": 18446743936271400350,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491349,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488928,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420213,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417792,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491269,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488848,
      "name": "cpu_maps_update_begin",
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
void cpu_maps_update_begin()
```

```json
{
  "name": "cpu_maps_update_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579523765,
      "name": "cpu_maps_update_begin",
      "external": true,
      "loc": "kernel/cpu.c:270",
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
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521232,
      "name": "cpu_maps_update_begin",
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

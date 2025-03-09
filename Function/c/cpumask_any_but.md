# Function: <code>cpumask_any_but</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945984,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:flush_tlb_current_task",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "mm/rmap.c:try_to_unmap_flush",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945984,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233008,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "arch/x86/mm/tlb.c:flush_tlb_current_task",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233008,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348080,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "arch/x86/mm/tlb.c:flush_tlb_current_task",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348080,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199344,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199344,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748176,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:51",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748176,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589125920,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:52",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125920,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360608,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:52",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360608,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817680,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817680,
      "name": "cpumask_any_but",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590044000,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044000,
      "name": "cpumask_any_but",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585037856,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037856,
      "name": "cpumask_any_but",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189760,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189760,
      "name": "cpumask_any_but",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073104,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073104,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519792,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519792,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672416,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_needs_fixup",
        "mm/rmap.c:try_to_unmap_one",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672416,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991270,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129224,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579485293,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579670796,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559788,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582877919,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590723984,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:339",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990552,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129544,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233254,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497901,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684743,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpu_down_maps_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633260,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083642,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590489957,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591065320,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579015431,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155864,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262102,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527741,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719255,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698412,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278271,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590840981,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591410072,
      "name": "cpumask_any_but",
      "external": false,
      "loc": "include/linux/cpumask.h:379",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503805096,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_offline_cpu",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_offline_cpu",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu",
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503805096,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236428244,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236428244,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297644160,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline",
        "arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297644160,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279701998,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279701998,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646256,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646256,
      "name": "cpumask_any_but",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372128,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372128,
      "name": "cpumask_any_but",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590089632,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590089632,
      "name": "cpumask_any_but",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```

```json
{
  "name": "cpumask_any_but",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590139888,
      "name": "cpumask_any_but",
      "external": true,
      "loc": "lib/cpumask.c:53",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/kernel/tsc.c:calibrate_delay_is_known",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590139888,
      "name": "cpumask_any_but",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int cpumask_any_but(const struct cpumask * mask, unsigned int cpu)
```
</details>
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

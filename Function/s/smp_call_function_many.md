# Function: <code>smp_call_function_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909024,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:404",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu",
        "kernel/smp.c:on_each_cpu_mask",
        "mm/rmap.c:try_to_unmap_flush",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909024,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938752,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:388",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938752,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969952,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:392",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_update_closid",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969952,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975312,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:401",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975312,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021792,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:403",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:SyS_membarrier",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021792,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075856,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:403",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075856,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123168,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:403",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123168,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168640,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168640,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216576,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216576,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580285551,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:574",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:drv_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285168,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580269071,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:712",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:drv_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268688,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580273103,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:988",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272976,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580425087,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:990",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/time/hrtimer.c:clock_was_set",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424960,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580648038,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:1009",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/time/hrtimer.c:clock_was_set",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647776,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915046,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:1008",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/time/hrtimer.c:clock_was_set",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914736,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581000678,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:856",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/time/hrtimer.c:clock_was_set",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000368,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096822,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:876",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/time/hrtimer.c:clock_was_set",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096512,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491455008,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491455008,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225441152,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_tlb.c:broadcast_tlb_mm_a15_erratum",
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225441152,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284405536,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/pgtable.c:pmdp_invalidate",
        "arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284405536,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271910984,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271910984,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185376,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185376,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132864,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132864,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176848,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176848,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
void smp_call_function_many(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "smp_call_function_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229040,
      "name": "smp_call_function_many",
      "external": true,
      "loc": "kernel/smp.c:412",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:smp_call_function",
        "arch/x86/lib/msr-smp.c:__rwmsr_on_cpus",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229040,
      "name": "smp_call_function_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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

# Function: <code>cpumask_clear_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879550,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983474,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579045021,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080310,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:amd_e400_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127482,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175023,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579180289,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196138,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214133,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo",
        "arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313422,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579322326,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323487,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376360,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:set_cpu_possible",
        "kernel/cpu.c:set_cpu_present",
        "kernel/cpu.c:set_cpu_online",
        "kernel/cpu.c:set_cpu_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465315,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527238,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_domains_numa_masks_update",
        "kernel/sched/core.c:rq_attach_root",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:idle_task_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579584388,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579632715,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638668,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648528,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579649972,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set",
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579755300,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805429,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_cpu_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880736,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control"
      ]
    },
    {
      "addr": 18446744071579909296,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461575,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580494900,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604489,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpuup_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613792,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022156,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582964432,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    },
    {
      "addr": 18446744071583038219,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584425209,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:cacheinfo_cpu_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585858323,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:280",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880736,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071582964432,
      "name": "cpumask_clear_cpu.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881761,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980189,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017264,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:stop_self"
      ]
    },
    {
      "addr": 18446744071579041081,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076198,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:amd_e400_remove_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ]
    },
    {
      "addr": 18446744071579127398,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171622,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175539,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579182548,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:smp_init_package_map",
        "arch/x86/kernel/smpboot.c:smp_init_package_map"
      ]
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579196680,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214719,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313284,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327923,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329119,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579388676,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479376,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579576761,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635319,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650705,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579655944,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664134,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665622,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579778164,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833202,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914408,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control"
      ]
    },
    {
      "addr": 18446744071579939017,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580536905,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584689,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252052,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    },
    {
      "addr": 18446744071583330812,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584173573,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584762105,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_callback",
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:free_cache_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586262700,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579017264,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579074096,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579177024,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579910272,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071583251728,
      "name": "cpumask_clear_cpu.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881825,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982161,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019136,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:stop_self",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579041063,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074551,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119902,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131625,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181718,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185967,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193047,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579208361,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226441,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328533,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343227,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344463,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409044,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505353,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579602857,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659875,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675365,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579680450,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688684,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690198,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805604,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827377,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861713,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944952,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control"
      ]
    },
    {
      "addr": 18446744071579970207,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580600506,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580651667,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367123,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455789,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354967,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584950965,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:free_cache_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586467050,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:284",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019136,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579940736,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881121,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991814,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013472,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579033876,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066759,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112064,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130828,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180646,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184873,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191245,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588343013,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223479,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322182,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337257,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338495,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396516,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497058,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579581234,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634279,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579649483,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654619,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674713,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676118,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681305,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803284,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827339,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869953,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952840,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control"
      ]
    },
    {
      "addr": 18446744071580552588,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630917,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684263,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583475678,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436518,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585035823,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586591658,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216169,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:307",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579013472,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579948656,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578882289,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994762,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014000,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579075861,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125360,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145196,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196118,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200524,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207102,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579240202,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345996,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362693,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363935,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424603,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523410,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579610578,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664648,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679142,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685083,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705449,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706742,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716313,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837419,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863140,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913345,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579998536,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control"
      ]
    },
    {
      "addr": 18446744071580632716,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580711957,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767698,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583656636,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844938,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458677,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587074906,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766121,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:311",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579014000,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579994368,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883843,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998637,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016656,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579025507,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579081269,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134133,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155529,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208025,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212416,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218472,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579252695,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357676,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375093,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376540,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439844,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547722,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579640498,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697369,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710163,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716500,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738359,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739733,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748019,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871287,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896130,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579957777,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580050616,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580759708,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580843605,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903970,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874602,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585075738,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585702227,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587372826,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589145161,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:313",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016656,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589144816,
      "name": "cpumask_clear_cpu.constprop.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883875,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996237,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018160,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579029603,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579086693,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145001,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195462,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231609,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236092,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242152,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579276503,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315902,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384846,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402757,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404204,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579473348,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579585296,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579678149,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579736320,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750259,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579757028,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579778119,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779493,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788051,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579918327,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943169,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580004609,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580097432,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580826172,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913189,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978618,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185370,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585830483,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587552666,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380297,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018160,
      "name": "cpumask_clear_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589379952,
      "name": "cpumask_clear_cpu.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885080,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004964,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026302,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037251,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579096439,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157908,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208343,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244937,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255989,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579289911,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331134,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400378,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418195,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419612,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490527,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579609346,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579710933,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579770802,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579778865,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786084,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805790,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807141,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815771,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956375,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981946,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047328,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137530,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920830,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010802,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:__padata_remove_cpu",
        "kernel/padata.c:__padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581401352,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585397979,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586065495,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586127002,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587827305,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837390,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886088,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579006468,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700684,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039571,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160404,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210599,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247129,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257653,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579295891,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335342,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403690,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421379,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422780,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474679,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516443,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635026,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579753285,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579811506,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579823028,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832212,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853358,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854709,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863547,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006231,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032204,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096432,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185674,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974286,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065074,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462344,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585538715,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586213383,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586276378,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588032329,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063534,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578890662,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011547,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609048402,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048899,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579182191,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231617,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271625,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284634,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579325763,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364736,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414502,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450603,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453052,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495386,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545276,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665591,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788037,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854053,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_exit_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864040,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870183,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892606,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579894021,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579904171,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056071,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580082077,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580158753,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251581,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141534,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581667608,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585060431,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586256551,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586978689,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587045450,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588893465,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:348",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886454,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014491,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612111746,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052195,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579178575,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224750,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279049,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291914,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579327363,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363760,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414773,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447867,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449980,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477811,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579526988,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645449,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779284,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579846229,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_exit_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856376,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863102,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579887191,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888741,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899083,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580038663,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064653,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143185,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235405,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181518,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703496,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591382083,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586374615,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587065249,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587129434,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588911561,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:354",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888374,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912002,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614251616,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057411,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579184831,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227150,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281817,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294634,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579330099,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369088,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417655,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450427,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452476,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579481474,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530364,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:bringup_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648901,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787436,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854357,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_exit_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863368,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872062,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896380,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897925,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908187,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039527,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065319,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580147857,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239889,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200030,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614432151,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724094,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591324518,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586259063,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586949035,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587015769,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588799721,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578915081,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615172053,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218949,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265806,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325028,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579341754,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579385054,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430080,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480618,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515419,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517809,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547547,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602616,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725687,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882194,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960389,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_exit_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975464,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982718,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580011236,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580013029,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580026955,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172087,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198751,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291941,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342370,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580389985,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440183,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615372251,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997320,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592238955,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592342653,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769639,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513706,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587581225,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589492286,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578921027,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088928,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267831,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318334,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384852,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402790,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579450686,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579498501,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579558886,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599098,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601729,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636699,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579695126,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579842435,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999392,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075384,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_exit_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116828,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:cpudl_clear_freecpu",
        "kernel/sched/build_policy.c:cpudl_set",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199730,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_clear",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318183,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351440,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580500341,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580555605,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580607486,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780620,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617160308,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419316,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586027279,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594204214,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588047620,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588840433,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918342,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590718483,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590971246,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:360",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578937331,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123696,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330695,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384910,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462100,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483190,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579538334,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579594885,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666134,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711468,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714545,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753907,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818922,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982019,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580161520,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580246600,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_exit_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290444,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:cpudl_clear_freecpu",
        "kernel/sched/build_policy.c:cpudl_set",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390594,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_clear",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532215,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580573700,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751845,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580814085,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871470,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582206593,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627845351,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582932290,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586862559,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589426324,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590343275,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590430198,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592390243,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592675710,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595856133,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:425",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578935683,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124056,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241276,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280069,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339527,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394542,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474676,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482334,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487515,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579551230,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607611,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679916,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724748,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579728177,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800488,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868309,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580034201,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580230486,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_mm_cid_before_execve",
        "kernel/sched/core.c:sched_mm_cid_remote_clear",
        "kernel/sched/core.c:sched_mm_cid_migrate_to",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:mm_cid_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580312499,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580357852,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:cpudl_clear_freecpu",
        "kernel/sched/build_policy.c:cpudl_set",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459187,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_clear",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605527,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834421,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897381,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955230,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446542,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:close_pipe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373793,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_clear_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406593,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619622156,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583148658,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128767,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588178495,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589725476,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590663488,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590749750,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592819315,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593106430,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596373013,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959043,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149959,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270124,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309973,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369655,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422926,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505439,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579512446,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517531,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579579102,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637227,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714364,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759612,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579763121,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833851,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906213,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580074832,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_pod_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279304,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_mm_cid_before_execve",
        "kernel/sched/core.c:sched_mm_cid_remote_clear",
        "kernel/sched/core.c:sched_mm_cid_migrate_to",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:mm_cid_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580365075,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580413420,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:cpudl_clear_freecpu",
        "kernel/sched/build_policy.c:cpudl_set",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_offline_rt",
        "kernel/sched/build_policy.c:pick_next_task_rt",
        "kernel/sched/build_policy.c:dequeue_task_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518835,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_clear",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670039,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807065,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread",
        "kernel/rcu/tree.c:rcu_nocb_cpu_deoffload"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923845,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987909,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046814,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621859517,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556078,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:close_pipe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541121,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_clear_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574817,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621926300,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333490,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587414911,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588469343,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589994646,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/pmdomain/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590063460,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591024064,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593568563,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859182,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597266373,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:485",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490275640,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:crash_smp_send_stop",
        "arch/arm64/kernel/smp.c:smp_send_stop",
        "arch/arm64/kernel/smp.c:cpu_die_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490361188,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:numa_update_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490388192,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:hardware_disable_nolock",
        "virt/kvm/kvm_main.c:hardware_enable_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490653840,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490801392,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490931124,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490992236,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491008676,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491019208,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491048800,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491051044,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491061328,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491202584,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491236984,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491305192,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410912,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492340112,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492426540,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492870848,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411164,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498112940,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498198028,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499020532,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499108392,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499202032,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501296836,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501590168,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501795712,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224451308,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm/kernel/devtree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224532240,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_active_store",
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus",
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3243308084,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm/mach-imx/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/platsmp.c:imx_smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm/mach-omap2/omap-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243347672,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/arm/mach-qcom/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-qcom/platsmp.c:qcom_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224730344,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224949880,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 3225001592,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225018312,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 3225025668,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 3225054576,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3225056464,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3225058616,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3225221584,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3225250048,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225303776,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225406800,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 3226218988,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3226307196,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226669620,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231582404,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231650900,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231733316,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 3233786484,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 3233829692,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_handle_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 3234031124,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 3234116412,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3236459608,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282340472,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kernel/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302390588,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kernel/setup-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282390280,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/watchdog.c:stop_watchdog",
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending",
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282412980,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282507648,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:set_cpus_unrelated",
        "arch/powerpc/kernel/smp.c:set_cpus_unrelated",
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi",
        "arch/powerpc/kernel/smp.c:smp_handle_nmi_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282595360,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282833252,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:unmap_cpu_from_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302494632,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/platforms/pseries/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/smp.c:smp_init_pseries",
        "arch/powerpc/platforms/pseries/smp.c:smp_setup_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283188568,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283281180,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:xmon_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283328936,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kvm/book3s_hv_rm_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283347152,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/powerpc/kvm/book3s_hv_builtin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_check_need_tlb_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283476348,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283637104,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283786076,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283862440,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283883960,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283893464,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283925544,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283927752,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283940144,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284105984,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284136912,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284231888,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284358436,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285566584,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285694112,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286263808,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292183120,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292284496,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294826124,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297691740,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/riscv/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271351908,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271360084,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/riscv/mm/cacheflush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/cacheflush.c:flush_icache_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271360354,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/riscv/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/context.c:switch_mm",
        "arch/riscv/mm/context.c:switch_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271566730,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:set_rq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271603794,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271615954,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271624304,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271645184,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271646868,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271648252,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271744046,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767412,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271816908,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272813820,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276387958,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276425394,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276492780,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886088,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579006820,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604626972,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039923,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160772,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209447,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245977,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256357,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291699,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331246,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399594,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417219,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418620,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490107,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611330,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579729205,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787282,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579796417,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579804564,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825710,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827061,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579835899,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974967,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000940,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065632,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154474,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580943086,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033922,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431192,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585300747,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973591,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586039626,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587657321,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665790,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879368,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972355,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579092292,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144423,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181417,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191573,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579227187,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265678,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329051,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346339,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579347756,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418971,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540402,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579657813,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718066,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579729780,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739076,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760286,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761637,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579770475,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912775,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939612,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010480,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100586,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604741671,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580888814,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580980002,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373624,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585822855,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585885642,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587431193,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574010,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:hv_process_channel_removal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391614,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886024,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579006404,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604704780,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039507,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160324,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210519,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247033,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257557,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292899,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331166,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399514,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417139,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418540,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490027,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579608610,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579714853,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579771874,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579783396,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792580,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579813726,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815077,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823915,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579966503,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992476,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056704,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145946,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580934334,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025122,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422392,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489115,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586163399,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586226394,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988473,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590109166,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_clear_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886376,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_dead",
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009348,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604704796,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043171,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579165460,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215799,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252601,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263157,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579301731,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339710,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408010,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426195,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427596,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480005,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522417,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650578,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579760949,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579819906,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579832445,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837572,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858846,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860197,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869035,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580013031,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039212,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107520,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197930,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995534,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087138,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486840,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585597115,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586272103,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586335818,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588103865,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159500,
      "name": "cpumask_clear_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask * dstp)
```
</details>
</li>
</ul>

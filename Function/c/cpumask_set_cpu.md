# Function: <code>cpumask_set_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879563,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594958000,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578905620,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier",
        "arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906994,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/events/intel/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578930985,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/events/intel/rapl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/rapl.c:rapl_cpu_init",
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934825,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978261,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023183,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078518,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:amd_e400_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104588,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132883,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176576,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579213471,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323407,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376644,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:set_cpu_possible",
        "kernel/cpu.c:set_cpu_present",
        "kernel/cpu.c:set_cpu_online",
        "kernel/cpu.c:set_cpu_online",
        "kernel/cpu.c:set_cpu_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595083568,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579520560,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_domains_numa_masks_update",
        "kernel/sched/core.c:rq_attach_root",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    },
    {
      "addr": 18446744071579624870,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628548,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638508,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579648493,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579649463,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/cpudeadline.c:cpudl_set",
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579755236,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805630,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_cpu_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881314,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910155,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580196991,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_cpu_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225315,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461422,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_add_cpu",
        "kernel/padata.c:padata_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580494832,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541680,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604630,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpuup_callback",
        "mm/vmstat.c:vmstat_cpuup_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613738,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm",
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849241,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022090,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582794497,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811747,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037414,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_free",
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129128,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749975,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info"
      ]
    },
    {
      "addr": 18446744071583755191,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ]
    },
    {
      "addr": 18446744071583838192,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584425706,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:cache_add_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863893,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884801,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896512,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585901238,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586263905,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586402872,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586407558,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:270",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176576,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579520560,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071583749975,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071583755191,
      "name": "cpumask_set_cpu",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879398,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595121534,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578906347,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932222,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978240,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019871,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:cpu_bringup"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_init"
      ]
    },
    {
      "addr": 18446744071579074480,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:amd_e400_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104086,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132958,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595195434,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579191049,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214208,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313228,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329039,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389275,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:disable_nonboot_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init"
      ]
    },
    {
      "addr": 18446744071595250935,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595257460,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579639183,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579643150,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579653708,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579664088,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665590,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595261780,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579778100,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799246,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833638,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912619,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939867,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580224113,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_cpu_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580262272,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584624,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630222,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974318,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073322,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583090883,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330006,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_free",
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423592,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584075942,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ]
    },
    {
      "addr": 18446744071584081280,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ]
    },
    {
      "addr": 18446744071584167264,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584173394,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584761952,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586265697,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586284382,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296330,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302186,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586688973,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586845633,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586850356,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579017248,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579177008,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579381680,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584075942,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584081280,
      "name": "cpumask_set_cpu",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879437,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595364283,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578906543,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933519,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980275,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020273,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:cpu_bringup"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_init",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ]
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579102562,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120246,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123320,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127087,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/cpu/intel_rdt_schemata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140451,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595438396,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579202545,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__generic_processor_info",
        "arch/x86/kernel/apic/apic.c:__generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225811,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328474,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344383,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409632,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init"
      ]
    },
    {
      "addr": 18446744071595494643,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595502099,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663775,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579667810,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678264,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579688648,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690166,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595506882,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805540,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827384,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860661,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943156,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579970987,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580275193,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580305310,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342321,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580651602,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697431,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048099,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187633,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_queue_reinit_prepare",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202315,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454937,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_free",
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583549220,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218408,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ]
    },
    {
      "addr": 18446744071584223860,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ]
    },
    {
      "addr": 18446744071584239942,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ]
    },
    {
      "addr": 18446744071584348537,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354786,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584952029,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586470128,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488438,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500602,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586508976,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586874895,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587036388,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587041313,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:274",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019120,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579187520,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579400768,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584218408,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584223860,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071584239942,
      "name": "cpumask_set_cpu",
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
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578878599,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596282689,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578926581,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984610,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014321,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579094319,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112837,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119168,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127230,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138628,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596359114,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579200310,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222883,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322080,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338415,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397020,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init"
      ]
    },
    {
      "addr": 18446744071596415354,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581382,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    },
    {
      "addr": 18446744071579638335,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579643432,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654049,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579674682,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676086,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683975,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596427195,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803220,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827346,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868917,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952292,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976378,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287481,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318426,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355064,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606596,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684198,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580731219,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581096587,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246981,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476345,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_free",
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583586948,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584292885,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584297890,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317296,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584429850,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436328,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585036884,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586594791,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612886,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586625144,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586633157,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586999377,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587164387,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587168748,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:291",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579013456,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579185824,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579388400,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579544912,
      "name": "cpumask_set_cpu",
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
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578880245,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602599035,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928960,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987382,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014865,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579104988,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126245,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132640,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141777,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153674,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602677255,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579216031,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239094,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346012,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363855,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425091,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init"
      ]
    },
    {
      "addr": 18446744071602740066,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610726,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668906,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674043,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684561,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579705418,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706710,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712487,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602748531,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602752084,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837355,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863147,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912306,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997988,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022815,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270170,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580340926,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371549,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408768,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580687332,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767633,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817287,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581208859,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426132,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657305,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_free",
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832995,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692024,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697007,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584716611,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837786,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844760,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585459628,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587061763,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587078109,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095942,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587108182,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587498051,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587674111,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:295",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579013984,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579201616,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579415728,
      "name": "cpumask_set_cpu",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578884064,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602767386,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931714,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989669,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017553,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579025216,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579110623,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135073,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140663,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152235,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164236,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602848717,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579228052,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251606,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357692,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376460,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441060,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init"
      ]
    },
    {
      "addr": 18446744071602912583,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579640646,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579702175,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708708,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717124,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579738324,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739701,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744404,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602920924,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602924611,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871223,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897088,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956721,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580050359,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076895,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330442,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402446,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580433084,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469770,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819316,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903905,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954302,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352130,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583637364,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874901,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_free",
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584033507,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584918018,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584923521,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944035,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585068441,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585075560,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703239,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587359967,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375915,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394283,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587406422,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587802786,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588003693,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:297",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016640,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579213504,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579430176,
      "name": "cpumask_set_cpu",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881840,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604561625,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933250,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988300,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019169,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579029312,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579116277,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153719,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196522,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204631,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218806,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604645522,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071579251748,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275414,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384871,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404124,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474564,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init"
      ]
    },
    {
      "addr": 18446744071604710191,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678300,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579741375,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579747828,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579756468,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579778084,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779461,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784335,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604718630,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604722536,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579918263,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944150,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003377,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580097175,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383706,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580457742,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580488727,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525850,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580885988,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978549,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030494,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435954,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742536,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584116243,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585021922,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585027425,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048019,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185166,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831495,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587539794,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555851,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574251,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587586342,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587938018,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588164351,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018144,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579237184,
      "name": "cpumask_set_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579463712,
      "name": "cpumask_set_cpu",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883022,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604655701,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938041,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998227,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688521,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036913,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579126096,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165791,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209437,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217550,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231974,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604744732,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265725,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289782,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400403,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419532,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604807481,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810534,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711085,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579771016,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776404,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785348,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579805755,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807109,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812967,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604823486,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956311,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982948,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046117,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580141082,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580436538,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512488,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544470,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582271,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983249,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094482,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581401280,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550895,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583931420,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305200,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585225613,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231192,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585252188,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585397856,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605055304,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586066565,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586126982,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587814596,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587830746,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850177,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862459,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588247456,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588492897,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578884046,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604668100,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940521,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999731,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700956,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039233,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127968,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168255,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211693,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219838,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234150,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604758131,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267373,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295750,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403715,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422700,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457954,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604841868,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604844809,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753437,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579811720,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579819884,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831460,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579853323,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071579854677,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860778,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604857835,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006167,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033106,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580095205,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580189226,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485306,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580560104,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580592022,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629375,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581037377,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151446,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462272,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071581615871,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034763,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439872,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585362045,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585367736,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390076,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585538592,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605092587,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586214453,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586276358,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588019796,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588035577,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054993,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588067243,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451616,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588700577,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888318,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609018695,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945707,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000661,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037221,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143278,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185214,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233830,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239673,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257542,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609104219,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:smp_callin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294976,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325622,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414485,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452972,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478688,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609176489,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609178302,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788189,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854744,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861476,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868840,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579892571,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893989,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579904049,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609188509,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056007,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083529,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157621,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254314,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570202,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580653256,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580659589,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730385,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216082,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337360,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581667536,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581830799,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584429671,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585003444,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586070465,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586075672,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099631,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586256422,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:enable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609379008,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586980190,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587045430,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588879284,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892658,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915745,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588928331,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589319856,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589563184,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:332",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883806,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612080996,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578947451,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002773,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040834,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140440,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181454,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226982,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233625,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249870,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612169137,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:smp_callin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301024,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327288,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414755,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449900,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612241923,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612243736,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779589,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579846952,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853812,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861608,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579887156,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888709,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898961,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612254856,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580038599,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066105,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142117,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580238170,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580557904,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580643768,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580650280,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719724,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258914,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703570,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877375,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584546074,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585124180,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586192401,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586197245,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586220223,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586374486,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:enable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612450497,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587066750,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587129414,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588892308,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588909250,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588928260,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588939579,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589318900,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349312,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589573208,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:338",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886326,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614219579,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578902551,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952347,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010069,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043666,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147385,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187278,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579229334,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235800,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251614,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614309649,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303888,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330011,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417680,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452396,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614382423,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:bringup_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614384312,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787741,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579855258,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862036,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870168,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579896345,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897893,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908065,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614396313,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039463,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066745,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146805,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194841,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243406,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561168,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646507,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580652504,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724819,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277601,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724168,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906564,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584578517,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585004744,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586067622,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072500,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586094782,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586259331,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614592165,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586950566,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587015749,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588781524,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588797299,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816582,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588828015,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589214564,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248983,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468715,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615137849,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578904484,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962823,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028110,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063842,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:set_cpu_possible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173650,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221930,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579268022,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278888,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292469,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615237453,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579351616,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384930,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480643,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517665,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615315252,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615317492,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882965,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961542,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974004,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579980359,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580011192,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012997,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580026815,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615330443,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172023,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200233,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290629,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580319384,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342252,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390982,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731200,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819115,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580826737,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905061,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521364,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997413,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582203220,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592238936,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584991563,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585446153,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586561819,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567412,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592687,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769907,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615549111,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587515865,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587581205,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589473764,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489696,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509987,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589523023,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936917,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973892,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590207244,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:309",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616901864,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905261,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971656,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048002,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087956,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217854,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272615,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579320374,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323956,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579347064,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617013276,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413536,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450552,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579558908,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601569,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617097033,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617099506,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999889,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076643,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580110612,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_clear",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199561,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617113957,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318103,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353434,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580498933,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580530809,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580555473,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609017,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580943944,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043727,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048086,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140568,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868857,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419401,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582666811,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585703073,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586027255,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586587663,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820759,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587824832,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851391,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588047909,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617354742,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843527,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918308,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590717883,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952290,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590973146,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994220,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591012641,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591020820,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591469804,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591491224,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591778298,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:344",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627497129,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919241,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989816,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078728,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122724,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276928,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337047,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579386534,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389850,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417301,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627644935,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495734,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539912,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666156,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714369,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627757725,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627761037,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580161861,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580247891,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580283972,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_clear",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390409,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627780412,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532119,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575750,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751125,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786979,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813950,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873501,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238056,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346740,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350182,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453517,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582296277,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582932346,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193739,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586482847,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586862535,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828463,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589163415,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167419,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197819,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589426643,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628091224,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590347641,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590430164,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592389627,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592654002,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592677677,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592701153,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592721891,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592731744,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593239418,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593271293,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593570703,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:409",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619241260,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923623,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989040,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078526,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619291114,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619337693,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_online",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345927,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579396182,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413589,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429375,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619401389,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507885,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551149,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679937,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579728001,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619518301,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619521869,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580210160,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313555,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351284,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_clear",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458995,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619543292,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605431,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833669,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870201,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897246,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956797,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333059,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/watchdog_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_perf.c:watchdog_hardlockup_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440916,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460753,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551021,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373729,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_set_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497045,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583148714,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411483,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586730417,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128743,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099583,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180534,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly",
        "lib/group_cpus.c:grp_spread_init_one",
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589456727,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589460821,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491979,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589725795,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590490003,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619856904,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590668458,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590749716,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591743023,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592818699,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593084802,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593108450,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593132182,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593158979,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593168880,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593700632,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727325,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594042687,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621531513,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953196,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013919,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104302,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621583672,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621630365,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_online",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372185,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579424630,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444337,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458959,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621696762,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530717,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:cpu_update_apic",
        "arch/x86/kernel/apic/apic.c:cpu_update_apic",
        "arch/x86/kernel/apic/apic.c:cpu_mark_primary_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579021,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714385,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579762945,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621815309,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_reset_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621819626,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_pod_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258480,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580366099,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374983,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/sched/build_policy.c:cpudl_clear",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_policy.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518643,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621842204,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580669943,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765826,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_nocb_cpu_offload"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923093,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960697,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987774,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048381,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439571,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/watchdog_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_perf.c:watchdog_hardlockup_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550196,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570001,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:print_trace_fmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663245,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541057,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_set_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665493,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333546,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__drain_all_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583391867,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587002177,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587414887,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435679,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588471377,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly",
        "lib/group_cpus.c:grp_spread_init_one",
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589764727,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589768821,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589799547,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589994612,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/pmdomain/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590063779,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590841027,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622165801,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591029738,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592486619,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593567938,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593837202,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593861393,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593885461,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593912787,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593922394,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594478376,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594507485,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594832975,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:469",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510823716,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:smp_prepare_cpus",
        "arch/arm64/kernel/smp.c:smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490361212,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:numa_update_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490393440,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:hardware_enable_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510874332,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510877756,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490931364,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490992612,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491002288,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491019348,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491048692,
      "name": "cpumask_set_cpu",
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
      "addr": 18446603336491050956,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491058036,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510891164,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491202464,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237932,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491305976,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491416636,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491847768,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491890832,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491933604,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492389848,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492528168,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492870512,
      "name": "cpumask_set_cpu",
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
      "addr": 18446603336493059204,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495867984,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496326828,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511073300,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411212,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497125272,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497128108,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497642288,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497663296,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498089924,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/soc/fsl/qbman/bman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498091444,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/soc/fsl/qbman/qman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498095032,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman.c:bman_create_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498112320,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_create_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498198340,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499021564,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499108356,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499200060,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501276376,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501278040,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501302740,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501590936,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501778476,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/perf/arm_pmu_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_platform.c:pmu_parse_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501779940,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/perf/arm_pmu_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501783100,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501795860,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501799056,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/perf/qcom_l3_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501806676,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501975540,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502262248,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224447724,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:secondary_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 3243271080,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/kernel/devtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 3224467284,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/hw_breakpoint.c:debug_reg_trap"
      ],
      "caller_func": []
    },
    {
      "addr": 3224511380,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/context.c:check_and_switch_context",
        "arch/arm/mm/context.c:a15_erratum_get_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3243291228,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/mm/cache-l2x0-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3224533104,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224580972,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/mach-imx/mmdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/mach-imx/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243332304,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/mach-omap2/omap-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/mach-qcom/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243355108,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/arm/mach-tegra/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus",
        "arch/arm/mach-tegra/platsmp.c:tegra_secondary_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243360944,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224950012,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 3225001964,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 3225012076,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 3225024388,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225054488,
      "name": "cpumask_set_cpu",
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
      "addr": 3225056424,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 3225062744,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3243379508,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3225221516,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3225250844,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225303736,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225410524,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 3225795436,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225833168,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 3225867792,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226277744,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226395396,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 3226669544,
      "name": "cpumask_set_cpu",
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
      "addr": 3226771812,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 3229215060,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 3229660440,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3243556792,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 3243836872,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/soc/qcom/spm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/spm.c:qcom_cpuidle_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231583824,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231650888,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231731832,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3233765720,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3233766544,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3233792560,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 3233830288,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_handle_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 3243918888,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpuidle/cpuidle-big_little.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle-big_little.c:bl_idle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234117160,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3234327980,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/perf/arm_pmu_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234729288,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3235002952,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282339012,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/kernel/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302390540,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/kernel/setup-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282388324,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/watchdog.c:start_watchdog",
        "arch/powerpc/kernel/watchdog.c:start_watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282515920,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:start_secondary",
        "arch/powerpc/kernel/smp.c:start_secondary",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:set_cpus_related",
        "arch/powerpc/kernel/smp.c:set_cpus_related",
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282624296,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/crash.c:crash_ipi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282729224,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/mmu_context.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282777688,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/mm/book3s64/radix_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282832856,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:map_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282943136,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282981216,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/platforms/powernv/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283080640,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/platforms/powernv/opal-imc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302494560,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/platforms/pseries/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/smp.c:smp_init_pseries",
        "arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283187600,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283281860,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:xmon_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283385056,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline",
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online",
        "arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online",
        "arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302504184,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302508540,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283786404,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283862828,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283873120,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283892324,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283925428,
      "name": "cpumask_set_cpu",
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
      "addr": 13835058055283927672,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283936032,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302525500,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284105808,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284137964,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284229280,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284363904,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284919008,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284972040,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285032008,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285651928,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285822892,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286263332,
      "name": "cpumask_set_cpu",
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
      "addr": 13835058055286500792,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290068124,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290645052,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292184872,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292284440,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294799728,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294801212,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294833916,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294860756,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295403492,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295757000,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270611756,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/riscv/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smpboot.c:smp_prepare_cpus",
        "arch/riscv/kernel/smpboot.c:setup_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271350906,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smp.c:riscv_cpuid_to_hartid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271360396,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/riscv/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/context.c:switch_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270616612,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271566904,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271604050,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271611848,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271623494,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271645112,
      "name": "cpumask_set_cpu",
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
      "addr": 18446743936271646794,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271651260,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270630928,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271743952,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767972,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271815134,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272148530,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272179326,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272208926,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272500948,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272581754,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272813888,
      "name": "cpumask_set_cpu",
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
      "addr": 18446743936272927536,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274993280,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275377510,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276389212,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276425368,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276491598,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277951202,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277952188,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278273958,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278496852,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578884046,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604594372,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940521,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000083,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604627244,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039585,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128352,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168607,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210541,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218686,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232998,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604684410,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266077,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291558,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399619,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418540,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604747135,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604750076,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729357,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787496,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794916,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803812,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579825675,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071579827029,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833130,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604762851,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974903,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001842,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064405,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580158026,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454106,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580528904,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580560822,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580598175,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006225,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120294,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431120,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071581584607,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584003499,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408608,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585162411,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167208,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585175596,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585300624,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604992188,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974661,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586039606,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587644788,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587660569,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679985,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058400,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588307313,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877806,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586026,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937497,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972017,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060016,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100225,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145549,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153518,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168278,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604651964,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201517,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226966,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329076,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579347676,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714752,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604717693,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657965,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718280,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579726524,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738212,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579760251,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071579761605,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767706,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730723,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912711,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940514,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009253,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580104138,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580401178,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580475784,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580507526,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544655,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952353,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067286,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373552,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071581526127,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939323,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343808,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585076603,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585081448,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117292,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604956511,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585823925,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585885622,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586263075,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/scsi/storvsc_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/storvsc_drv.c:storvsc_channel_init",
        "drivers/scsi/storvsc_drv.c:handle_sc_creation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587418660,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587434441,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587454065,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587466331,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572477,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:init_vp_index",
        "drivers/hv/channel_mgmt.c:init_vp_index",
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587771488,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020129,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883982,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604672196,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940457,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999667,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604705052,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039169,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127904,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168175,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211613,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219758,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234070,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604761994,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267277,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292758,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399539,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418460,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824702,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604827643,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715005,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579772088,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780252,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579791828,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579813691,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071579815045,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821146,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604840479,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579966439,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579993378,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580055477,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580149498,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580445354,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520152,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552070,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589423,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580997425,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581111494,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422320,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071581575919,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583987259,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584391520,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585313629,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585319320,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340476,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585488992,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605072910,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164469,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586226374,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587975940,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587991721,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588011137,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588023387,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390176,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588639137,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "cpumask_set_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578884334,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/amd/uncore.c:uncore_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604672216,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941033,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002469,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604705068,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042833,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133024,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173359,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216893,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225054,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239510,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604762251,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272877,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301590,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408035,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427516,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463474,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604846025,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604848978,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761101,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820120,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825936,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836820,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579858811,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071579860165,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866266,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604861976,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012967,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580040114,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106229,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580201480,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580500986,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576600,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608790,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646319,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058513,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173974,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486768,
      "name": "cpumask_set_cpu",
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
      "addr": 18446744071581641167,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584089563,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497584,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585419773,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585425464,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585447788,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596992,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605096781,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586273173,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586335798,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588091316,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588107145,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588126609,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588138859,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525925,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588778630,
      "name": "cpumask_set_cpu",
      "external": false,
      "loc": "include/linux/cpumask.h:325",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
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
void cpumask_set_cpu(unsigned int cpu, struct cpumask * dstp)
```
</details>
</li>
</ul>

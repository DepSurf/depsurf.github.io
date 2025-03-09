# Function: <code>bitmap_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578907348,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "arch/x86/events/intel/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931079,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "arch/x86/events/intel/rapl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594967810,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578978279,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579045248,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193037,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579376983,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465320,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595089825,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621703,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743036,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579772383,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880997,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002202,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:cpuset_write_s64",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491850,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580571670,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580863696,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964855,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799835,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583801966,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583803607,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584341249,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584423972,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851428,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_frequency_get_table",
        "drivers/cpufreq/cpufreq.c:first_policy",
        "drivers/cpufreq/cpufreq.c:first_policy",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_finish",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585881855,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:282",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578980046,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041327,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197071,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579389607,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502602,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595257431,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636141,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587834646,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765200,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795567,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913167,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580045377,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_s64",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:update_domain_attr_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576530,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580664486,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753334,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580992550,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583251949,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584126101,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584128223,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129888,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584689361,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584759755,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586256110,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586282079,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578981934,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041252,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119912,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208767,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595477486,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410003,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523308,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595502069,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660579,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588049974,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792365,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579822760,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943689,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083645,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_s64",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:update_domain_attr_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642972,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731788,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580818672,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023704,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066306,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077084,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367299,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584274101,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584276223,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584277888,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584875921,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584951318,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586465246,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586486008,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991580,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033927,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112077,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127286,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206292,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596399084,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397395,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579511146,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596421823,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683991,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277113,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789749,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821548,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949112,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580089437,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580675488,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767772,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859120,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069542,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114444,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124350,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584352211,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354191,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584355882,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584964932,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585036191,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586590062,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586610552,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588204773,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216363,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578994520,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018621,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125373,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141833,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222838,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602718755,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425459,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538074,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712501,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746422,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071588843010,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823073,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856924,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579857463,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994824,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142712,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580611423,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580615215,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580760666,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855129,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950128,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180678,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225468,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236958,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583412546,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584758003,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584759983,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584761674,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386228,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585459023,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587061819,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587073038,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587093592,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588753721,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766315,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:310",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746422,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578998389,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579021675,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024437,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579134146,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152279,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235074,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602891461,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440367,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579564490,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744414,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780790,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071589222129,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856849,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890508,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890942,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046920,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580202015,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720799,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722319,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896466,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993221,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086311,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325494,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373212,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382702,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583621356,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584986845,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584988538,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584990438,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585628718,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585702574,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425878,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587360021,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371114,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587392061,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132019,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589145052,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:341",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780790,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578995989,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024575,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028528,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195475,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218861,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226246,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258738,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314536,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688819,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579473871,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601722,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784345,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823670,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071589464289,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579903809,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937580,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938007,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948069,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093752,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253498,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800935,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802484,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971186,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070677,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164215,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409606,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437236,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466814,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583725964,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215681,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585091213,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092906,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585094798,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755918,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585830830,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586571104,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587539893,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587551002,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572013,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589365917,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380188,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589428970,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823670,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579004730,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032991,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036540,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208357,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232029,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239432,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272846,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330520,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604788592,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491151,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579625018,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579808868,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851878,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071589924369,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938626,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976156,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976609,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579986725,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137623,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580295852,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134142,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235097,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389068,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521797,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589950314,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552172,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581550,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914488,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584404518,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295635,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585297532,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585299028,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987699,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586065851,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797123,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822642,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814693,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825674,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587847870,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589823051,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837244,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589886621,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:342",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851878,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579006234,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035311,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038860,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210613,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234205,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241656,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262521,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275443,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334760,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604814294,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517087,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651050,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858021,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900406,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071590150481,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579989154,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025676,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580026113,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580036853,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185767,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580344204,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191886,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293561,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450636,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581586501,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177876,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617166,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647262,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017704,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584540202,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585433603,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435500,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585436996,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134707,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586213739,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586943075,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586968738,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588019893,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588030986,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588052686,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590049035,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063388,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590112573,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900406,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579011434,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579045941,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048396,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231630,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257597,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265368,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289266,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301104,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364184,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609151492,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579546383,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682552,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892255,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901221,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_balance_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943558,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071580031489,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ]
    },
    {
      "addr": 18446744071580035650,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580049626,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076172,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076571,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580088373,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251687,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426610,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375724,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581483753,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656246,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798469,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071591196028,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581832119,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581864062,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584415692,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585043383,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585060284,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585111826,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585213157,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586148857,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586152362,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586153657,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586890348,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586979077,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587756307,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587792293,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588879381,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588896107,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588913102,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589871773,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589892029,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:382",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943558,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580030032,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581776704,
      "name": "bitmap_empty.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579014356,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049377,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051724,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224763,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249899,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257768,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295330,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306512,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363208,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612221827,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579528079,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662456,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886873,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888267,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896085,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_balance_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591290873,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071580015201,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ]
    },
    {
      "addr": 18446744071580018802,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032186,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058300,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058699,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071659,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235511,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414098,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419547,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525081,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704406,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846373,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071591690920,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878741,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909474,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585195111,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209724,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585261330,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585364838,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267065,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586270428,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586271673,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586940796,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587065637,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587815872,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850309,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892438,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908036,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588925502,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589570035,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589911501,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589931181,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591290873,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580013616,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581824224,
      "name": "bitmap_empty.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881039,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578902535,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014466,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052208,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056924,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227162,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251643,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259209,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298379,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308592,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368520,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614362694,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579532367,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669050,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896059,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897445,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579904597,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591233953,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071614396404,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580019970,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033082,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059004,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059403,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072376,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194893,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240002,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414036,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440811,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614432095,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547241,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724800,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756330,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581877159,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071591633952,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909492,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585078199,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092700,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585144909,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585248495,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141257,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586144297,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586145577,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822403,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586949445,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695088,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587730480,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781654,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588794718,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588813934,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468006,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589816973,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589839252,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589861952,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:380",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591233953,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581854864,
      "name": "bitmap_empty.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578884747,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578904468,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032802,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265818,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292372,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300353,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345867,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357120,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429416,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615293507,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579604655,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746043,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010851,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012515,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022341,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:asym_cpu_capacity_scan",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592121257,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071615330534,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580152530,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165610,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580191564,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580191963,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206216,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592154655,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580390098,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580578324,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694674,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615372133,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810477,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027194,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037590,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582168775,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071592807964,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201054,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245677,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585525047,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585540300,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585597741,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585704477,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586642461,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586645625,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586646921,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382547,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587514357,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588286599,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588323984,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589473894,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589487053,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589506831,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590206694,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579293,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590601964,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590622995,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592121257,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592154655,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582147168,
      "name": "bitmap_empty.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578882441,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905245,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053183,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318346,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338224,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346884,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355743,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372613,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407381,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_pending_intr_clear",
        "arch/x86/kernel/apic/apic.c:apic_pending_intr_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420240,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497693,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579600450,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617072988,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617076786,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636211,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697357,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850275,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997502,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106127,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194454,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071617114256,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298593,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311866,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336889,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580341896,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342231,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352091,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580360440,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553136,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580609593,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580779248,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902063,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066862,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617159002,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617160190,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582199341,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582454446,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466214,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582626472,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071594709042,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665927,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716414,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586678298,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694967,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586755981,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586872461,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909201,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587912577,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587913946,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692620,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588842045,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589171822,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589673482,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589714354,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952831,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590974699,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq.c:show",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590990623,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591781647,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592196967,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592222252,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592245013,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:406",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593883870,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580553136,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582601840,
      "name": "bitmap_empty.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887637,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919225,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084283,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384922,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406991,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417127,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426223,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449781,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488889,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503568,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579594061,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711733,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:leave_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627725052,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627729852,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752909,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821919,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990909,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159502,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180401,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279411,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385285,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580503553,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510529,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525194,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553857,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559400,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559767,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574395,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583400,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580814367,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580872172,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067220,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582335937,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538994,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627843759,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627845261,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582686045,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968086,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980940,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583150888,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596452936,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190916,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596458288,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020865,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589260346,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589263953,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265402,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171420,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590344221,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590724318,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591284958,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591331226,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592654853,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592679403,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq.c:show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592696751,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593574338,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594025255,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594052620,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594077573,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595758496,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595856391,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595922605,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:420",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885669,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923472,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084491,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394554,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409180,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429239,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438134,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461941,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482343,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501105,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515840,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606765,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725013,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:leave_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619483266,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619489072,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799619,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871039,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044621,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207918,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580245130,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580346710,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454056,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575224,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582657,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580627089,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632872,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633239,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580656312,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897663,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580957581,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157572,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach_check",
        "kernel/cgroup/cpuset.c:cpuset_can_attach_check",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581461190,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374533,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537153,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748594,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619608255,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619622066,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582895629,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583116511,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_ram_vread_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583180518,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583192556,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583361240,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596994264,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408948,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596999648,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588179182,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588295263,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589557258,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589560749,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589562106,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590485644,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590491667,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590664285,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591065646,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635163,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591651400,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591675880,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692603,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593085621,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593110443,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq.c:show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593127711,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594055735,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594402855,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594431916,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594456085,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethtool_link_modes_to_fecparam"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596282832,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596373272,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596441328,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:418",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578907973,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952794,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110283,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422938,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438133,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458823,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467718,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492005,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579512455,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531364,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579544560,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636397,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759877,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:leave_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621779586,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621785888,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833335,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908959,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081153,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wqattrs_actualize_cpumask",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580256238,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291401,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_energy_efficient_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580401401,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580513657,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580639512,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646785,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692145,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698024,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698391,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580721528,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621851594,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580988191,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581049165,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263076,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach_check",
        "kernel/cgroup/cpuset.c:cpuset_can_attach_check",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:reset_partition_data",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask"
      ]
    },
    {
      "addr": 18446744071581570445,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541861,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706017,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916530,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621912431,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621926210,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067501,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583299407,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_ram_vread_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583364292,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583377652,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388676,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583597688,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597923656,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597928992,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470030,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588589063,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589866442,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589869933,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589871338,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590836966,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590842691,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591024861,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591410445,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592375755,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592392648,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592418280,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592435611,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593838021,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593863457,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq.c:show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593880879,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594846231,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595204519,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595234172,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258357,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethtool_link_modes_to_fecparam"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597167419,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597266632,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597336688,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:395",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227920,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510836280,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490403796,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490655204,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490823952,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491055044,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510887080,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503902164,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491180700,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491193616,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491229884,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410976,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491607964,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492573132,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492700000,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492857196,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493023928,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503920672,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493061516,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495850524,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496398040,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496726172,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497715236,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497717696,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497719560,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498134664,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:tcs_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498871976,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/iommu/arm-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499018916,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499200984,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499926260,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499960024,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501276564,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501282428,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501287144,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501799376,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/perf/qcom_l3_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501806820,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503825396,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503894040,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224451312,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3243272044,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224731716,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224838460,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3225059856,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 3243374796,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3236529760,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225201936,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3225214624,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 3225243900,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225249552,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225406880,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3225570060,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 3226435576,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 3226538080,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 3226772628,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 3229196776,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3229726964,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3230016760,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 3231580936,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 3231732604,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232470724,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3232498980,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 3233765828,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3233771168,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233777476,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/cpufreq.c:show_cpuinfo_cur_freq",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 3233830828,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:cpuidle_coupled_unregister_device",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3234031032,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 3236445404,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3236459788,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 3236523200,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282340488,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/kernel/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282389468,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending",
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282412768,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282499916,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/iommu.c:iommu_take_ownership",
        "arch/powerpc/kernel/iommu.c:iommu_tce_table_put"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282510484,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi",
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi",
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282838104,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/mm/slice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282943216,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283045964,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283187736,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283262500,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:cpus_are_in_xmon"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283478164,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283658604,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283932748,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302520624,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284072436,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284078780,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284097084,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284358640,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284592396,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285882552,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286033748,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286246320,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286453676,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297815660,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate",
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286502496,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286545024,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290043288,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290816620,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292181340,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293244048,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293285460,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294799988,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294807732,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294814576,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297669516,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297692044,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297761716,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271360178,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/riscv/mm/cacheflush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/cacheflush.c:flush_icache_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271361442,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/riscv/mm/tlbflush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/tlbflush.c:flush_tlb_range",
        "arch/riscv/mm/tlbflush.c:flush_tlb_page",
        "arch/riscv/mm/tlbflush.c:flush_tlb_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271484126,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271649372,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270628006,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279790378,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271727758,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767116,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272012042,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272614464,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272701430,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272881952,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272928356,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274977562,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275483388,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276386220,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277012030,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277039114,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277951364,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277956358,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279718896,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279784262,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579006586,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035663,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039212,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209461,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233053,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240504,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261225,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274147,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330664,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728236,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490751,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627354,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830373,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872518,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071589752769,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957890,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994412,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994849,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005589,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154567,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313004,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160734,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581262409,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419484,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555237,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780164,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585902,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615998,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583986440,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497130,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585196131,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198028,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585199524,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585895075,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973947,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586700083,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586725746,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587644885,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587655978,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587677678,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589651291,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665644,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589714829,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872518,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578968527,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971248,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144437,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168333,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176088,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196585,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209491,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265128,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695966,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419615,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555706,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764949,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807526,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071589476993,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895746,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579928903,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933084,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933521,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944261,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735737,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100679,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580260332,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107598,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209065,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361996,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581496885,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589502987,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527422,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557326,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922296,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584435258,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585148339,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585150236,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585151732,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754811,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585823211,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586568435,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592962,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587418757,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587429850,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587451150,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572533,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589377099,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391468,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589440605,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807526,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579006170,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035247,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038796,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210533,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234125,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241576,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262425,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275347,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330584,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604805803,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490671,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579624634,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818389,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860678,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071590196177,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949426,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985948,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579986385,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997125,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146039,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580304252,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151934,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253609,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410684,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546549,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223572,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577214,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607310,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583970200,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584491866,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585384003,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585385900,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585387396,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084723,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586163755,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586897635,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586923298,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587976037,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587987130,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588008830,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590094667,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590109020,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590158205,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860678,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579009082,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038815,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042444,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215813,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239565,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247144,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268025,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281239,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339128,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818422,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523071,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579658282,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863509,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906054,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_init"
      ]
    },
    {
      "addr": 18446744071590246609,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579996466,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032604,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033039,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580043973,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198023,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580358695,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214670,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317433,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474476,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611669,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590273930,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642462,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673710,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072321,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584598131,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585491347,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493244,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585494740,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:options_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193011,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586272459,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587004019,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029746,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091413,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588102522,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588124270,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590144923,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159344,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590208781,
      "name": "bitmap_empty",
      "external": false,
      "loc": "include/linux/bitmap.h:366",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906054,
      "name": "bitmap_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
bool bitmap_empty(const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool bitmap_empty(const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bitmap_empty(const long unsigned int * src, unsigned int nbits)
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

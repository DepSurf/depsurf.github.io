# Function: <code>find_first_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583030944,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:82",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier",
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier",
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_set_distance",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:init_workqueues",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/rt.c:find_next_push_cpu",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/cgroup.c:cgroup_calc_child_subsys_mask",
        "kernel/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_can_fork",
        "kernel/cgroup.c:cgroup_post_fork",
        "kernel/cgroup.c:cgroup_exit",
        "kernel/cgroup.c:cgroup_free",
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:cpuset_write_s64",
        "kernel/cpuset.c:cpuset_spread_node",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_index_to_cpu",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/mmzone.c:first_online_pgdat",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:list_lru_destroy",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:next_node_allowed",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:policy_zonelist",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/buffer.c:free_more_memory",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq-tag.c:bt_tags_for_each",
        "block/blk-mq-tag.c:bt_for_each",
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map",
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "lib/bitmap.c:bitmap_remap",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpio-zx.c:zx_irq_handler",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/dimm_devs.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_register_device",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/cpufreq/cpufreq.c:cpufreq_frequency_get_table",
        "drivers/cpufreq/cpufreq.c:first_policy",
        "drivers/cpufreq/cpufreq.c:first_policy",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_finish",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "arch/x86/power/cpu.c:bsp_pm_callback",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030944,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323408,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:82",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:numa_set_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/rt.c:find_next_push_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/affinity.c:irq_create_affinity_mask",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup.c:cgroup_free",
        "kernel/cgroup.c:cgroup_exit",
        "kernel/cgroup.c:cgroup_post_fork",
        "kernel/cgroup.c:cgroup_can_fork",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:rebind_subsystems",
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
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_index_to_cpu",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:list_lru_destroy",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:policy_zonelist",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/buffer.c:free_more_memory",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq-tag.c:bt_tags_for_each",
        "block/blk-mq-tag.c:bt_for_each",
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map",
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/nodemask.c:__next_node_in",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpio-zx.c:zx_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:rand_initialize",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "arch/x86/power/cpu.c:bsp_pm_callback",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323408,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448320,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:82",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/rt.c:find_next_push_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup.c:cgroup_free",
        "kernel/cgroup.c:cgroup_exit",
        "kernel/cgroup.c:cgroup_post_fork",
        "kernel/cgroup.c:cgroup_can_fork",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:rebind_subsystems",
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
        "kernel/cpuset.c:update_domain_attr_tree",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:setup_vmstat",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:list_lru_destroy",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/buffer.c:free_more_memory",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq-cpumap.c:get_first_sibling",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:rand_initialize",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "arch/x86/power/cpu.c:bsp_pm_callback",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448320,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468960,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:82",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/rt.c:find_next_push_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_create",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/buffer.c:free_more_memory",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_next_cpu",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:rand_initialize",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_remove",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468960,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649888,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:82",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/devmap.c:__dev_map_flush",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/memremap.c:order_at",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_create",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_next_cpu",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:rand_initialize",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_remove",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649888,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583867920,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:102",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/devmap.c:__dev_map_flush",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/memremap.c:order_at",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_remove",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867920,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953200,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:102",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:update_domain_attr_tree",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/devmap.c:__dev_map_flush",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953200,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132960,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:98",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/soundwire/bus.c:sdw_handle_slave_alerts",
        "drivers/soundwire/bus.c:sdw_handle_slave_alerts",
        "drivers/soundwire/bus.c:sdw_handle_slave_alerts",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132960,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255360,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:98",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/vmalloc.c:s_show",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255360,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663120,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:106",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts",
        "arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:nearby_node",
        "arch/x86/kernel/cpu/hygon.c:nearby_node",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:init_sched_groups_capacity",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/stats.c:schedstat_next",
        "kernel/sched/debug.c:sched_debug_next",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/power/energy_model.c:em_create_pd",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:get_nodes_in_cpumask",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/vmalloc.c:s_show",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:init_kmem_cache_nodes",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_alloc_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_one_shrinker_map",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_all",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/proc/task_mmu.c:show_numa_map",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_remap",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/gpio/gpio-msic.c:msic_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/pcie/aer.c:__aer_print_error",
        "drivers/pci/pcie/aer.c:__aer_print_error",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:pnp_print_irq",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_timer_set_irq",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx",
        "drivers/input/input.c:input_estimate_events_per_packet",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663120,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780480,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:108",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:icl_update_topdown_event",
        "arch/x86/events/intel/core.c:update_saved_topdown_regs",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts",
        "arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:nearby_node",
        "arch/x86/kernel/cpu/hygon.c:nearby_node",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/apic.c:apic_check_and_ack",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor",
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:init_sched_groups_capacity",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/stats.c:schedstat_next",
        "kernel/sched/debug.c:sched_debug_next",
        "kernel/sched/debug.c:sd_ctl_doflags",
        "kernel/sched/debug.c:sd_ctl_doflags",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:get_nodes_in_cpumask",
        "kernel/irq/affinity.c:irq_spread_init_one",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/vmalloc.c:s_show",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:allowed_mems_nr",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:init_kmem_cache_nodes",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_alloc_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_one_shrinker_map",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/io-wq.c:io_wq_cpu_online",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/proc/task_mmu.c:show_numa_map",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_remap",
        "lib/pldmfw/pldmfw.c:pldm_send_component_tables",
        "lib/cpumask.c:cpumask_any_distribute",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/gpio/gpio-msic.c:msic_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/pcie/aer.c:__aer_print_error",
        "drivers/pci/pcie/aer.c:__aer_print_error",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/pnp/manager.c:pnp_assign_irq",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:pnp_print_irq",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_timer_set_irq",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx",
        "drivers/input/input.c:input_estimate_events_per_packet",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:handle_update",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table",
        "net/core/dev.c:dev_change_proto_down_reason",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/devlink.c:__devlink_reload_stats_update",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780480,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881052,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578884973,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578901587,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:hybrid_format_is_visible",
        "arch/x86/events/intel/core.c:hybrid_tsx_is_visible",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:init_hybrid_pmu",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:update_saved_topdown_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921321,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928412,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939577,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578956785,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978009,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614232591,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014473,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052214,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056930,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614269634,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144545,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175178,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177752,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192163,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209343,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217754,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227168,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239266,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250014,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251609,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260684,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292572,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298379,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308599,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324400,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614336888,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368520,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614358566,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450422,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614364864,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614365752,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478645,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532373,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614384139,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718109,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779497,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579857754,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890611,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896066,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909008,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains"
      ]
    },
    {
      "addr": 18446744071579917727,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stats.c:schedstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919503,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/debug.c:sd_flags_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579934825,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591233960,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:bitmap_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579978598,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990101,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/power/poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/poweroff.c:handle_poweroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614396334,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580020152,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033088,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059011,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059403,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065560,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072390,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580193754,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580238757,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_handover_do_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240008,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
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
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374010,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580395716,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414043,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
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
      "addr": 18446744071580434431,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670547,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724703,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978966,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082266,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203968,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303502,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315749,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581356424,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614430517,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479941,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:first_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614431056,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614432095,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614438320,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581553681,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706345,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614444981,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756330,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614449116,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807521,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834849,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877159,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591634606,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909492,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614459029,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_lruvec_page_state",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274696,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655146,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_cpu_online",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_exit_workers",
        "fs/io-wq.c:io_wq_exit_workers",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838104,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582920323,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583970764,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583989161,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584022907,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584038678,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584578865,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592019,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584781843,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585065225,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585072936,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_distribute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585078199,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092707,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092897,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585127448,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585200355,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585211880,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585217334,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585224227,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585248495,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585279648,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585364815,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_for_each_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585408996,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591342483,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:__aer_print_error",
        "drivers/pci/pcie/aer.c:__aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614540305,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774449,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586082046,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141257,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586144297,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586145577,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207349,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586224272,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/dma/lgm/lgm-dma.c:dma_interrupt",
        "drivers/dma/lgm/lgm-dma.c:ldma_dev_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614558857,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586291047,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586293409,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591395469,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586459821,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:moom_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586480513,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586647819,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586667926,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_timer_set_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586791137,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822403,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586949452,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
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
      "addr": 18446744071587040833,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092687,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587236016,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:commands_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587251539,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:commands_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587297510,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587441095,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/scsi/scsi_debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695088,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587730480,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588119408,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588300630,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588315041,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588364684,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_estimate_events_per_packet",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588380225,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/input/ff-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/ff-core.c:input_ff_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588416706,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/input/misc/uinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588487742,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781654,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588794725,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588819973,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589231336,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_proto_down_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468013,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589634825,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_reload_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589810874,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589839252,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589861952,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591174548,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:109",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898800,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578884760,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889203,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578903235,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:hybrid_format_is_visible",
        "arch/x86/events/intel/core.c:hybrid_tsx_is_visible",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:init_hybrid_pmu",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:update_saved_topdown_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926553,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933404,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578946817,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967401,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993453,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615151412,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032809,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615191808,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171617,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208847,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211794,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227315,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246655,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255963,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265824,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276558,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290603,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292464,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301898,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338294,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343432,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345867,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357127,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378848,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615267903,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429416,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615289012,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515414,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615296095,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615297060,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579544709,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604661,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615317316,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:__queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796448,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872953,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965642,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005271,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010858,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580027833,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:asym_cpu_capacity_scan",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_perf_domains"
      ]
    },
    {
      "addr": 18446744071580040303,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stats.c:schedstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580041535,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/debug.c:sd_flags_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059143,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592121264,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:bitmap_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580110035,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122037,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/power/poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/poweroff.c:handle_poweroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615330464,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580152712,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165616,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580191571,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580191963,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199032,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206230,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580339610,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:bitmap_empty"
      ]
    },
    {
      "addr": 18446744071580388261,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_handover_do_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390104,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
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
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580535116,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580557844,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580578331,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
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
      "addr": 18446744071580599215,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580845475,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904994,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190683,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310644,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443744,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548136,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561005,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581604277,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615370411,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734405,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:first_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615370954,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615372139,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615379271,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817169,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978217,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615387623,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037590,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615391896,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092833,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124625,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582168775,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592808368,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201054,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245544,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/migrate.c:__disable_all_migrate_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615404076,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593176,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987138,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_max_workers",
        "fs/io-wq.c:io_wq_cpu_affinity",
        "fs/io-wq.c:__io_wq_cpu_online",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170822,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254931,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584336316,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584356073,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584392933,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584409789,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991939,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585006523,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585212307,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_ord_to_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585511865,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585519624,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_distribute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585525047,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585540307,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585540487,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585577192,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585654984,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585667048,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585672342,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679575,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585704477,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585736193,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585824227,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_for_each_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871078,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585883636,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:__aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615491894,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586257446,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579153,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586642461,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586645625,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586646921,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586713429,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586730565,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/dma/lgm/lgm-dma.c:dma_interrupt",
        "drivers/dma/lgm/lgm-dma.c:ldma_dev_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615513057,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586807900,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586811459,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592440261,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586915346,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/regulator/irq_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586986717,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:moom_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009443,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587195465,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587216134,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_timer_set_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587347870,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382547,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587514364,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
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
      "addr": 18446744071587608545,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664727,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587802288,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:commands_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817171,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:commands_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587864118,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588014615,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/scsi/scsi_debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588286599,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588323984,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588753792,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588957796,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588972496,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589028521,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_estimate_events_per_packet",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589044401,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/input/ff-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/ff-core.c:input_ff_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589083733,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/input/misc/uinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589156229,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589473894,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589487060,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589513722,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957372,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_proto_down_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590206701,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590388585,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_reload_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590577306,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd",
        "net/ethtool/ioctl.c:ethtool_virtdev_validate_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590601964,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590622995,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592028068,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:110",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014032,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580338656,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868937,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578907667,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:hybrid_format_is_visible",
        "arch/x86/events/intel/core.c:hybrid_tsx_is_visible",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934039,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578955476,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053190,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218721,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260435,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262666,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298415,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318353,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330270,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
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
      "addr": 18446744071579345067,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579347059,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357361,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372613,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398992,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404386,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407381,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_pending_intr_clear",
        "arch/x86/kernel/apic/apic.c:apic_pending_intr_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420247,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579443336,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617043816,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497693,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617068359,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579600456,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617075959,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617076786,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579633397,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636217,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697363,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617099344,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905321,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997502,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580080969,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580135406,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200867,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:sched_debug_start",
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_perf_domains"
      ]
    },
    {
      "addr": 18446744071580249968,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580262933,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/power/poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/poweroff.c:handle_poweroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580264855,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617114188,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298767,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311872,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336893,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580341903,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342231,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352091,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580360454,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553539,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605983,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_handover_do_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609600,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
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
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580779255,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
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
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
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
      "addr": 18446744071580802516,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120259,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/trace/pid_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/pid_list.c:trace_pid_list_clear",
        "kernel/trace/pid_list.c:trace_pid_list_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140611,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609713,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900435,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912941,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581964445,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617158364,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115413,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:first_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617158938,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617160196,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617168088,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208740,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582386273,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617177486,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466214,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617182182,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570309,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582626472,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:policy_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594709455,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665927,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:init_kmem_cache_nodes",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582708310,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:param_set_sample_interval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716107,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/migrate.c:__disable_all_migrate_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617196149,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872515,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123384,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662193,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583754986,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584957260,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584979017,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585018885,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585036696,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703684,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585721832,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586037543,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_max_workers",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:__io_wq_cpu_online",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586048246,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_ord_to_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586165842,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586662470,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586672147,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_distribute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586678298,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694974,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695190,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586872461,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587912577,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587913946,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588050017,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617317120,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588090752,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588093959,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588242186,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284461,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:moom_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617348903,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692620,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588842052,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617358408,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589171822,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589673482,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952831,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590974706,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591002668,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257406,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_parent_cpu_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591781653,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592245013,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593603898,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593795421,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:116",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:bsp_pm_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593879896,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
  "name": "find_first_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875433,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922451,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:hybrid_format_is_visible",
        "arch/x86/events/intel/core.c:hybrid_tsx_is_visible",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948021,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972244,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084290,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274449,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322644,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324934,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356833,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364703,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382601,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384929,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394510,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
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
      "addr": 18446744071579414965,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417296,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427542,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449781,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478504,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579485040,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488889,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503575,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529336,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627684541,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579594061,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627717015,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711746,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:leave_uniprocessor",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627729093,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627729852,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579747989,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752915,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821925,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627760856,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058089,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159502,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252489,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_cpu_capacity",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580309792,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391875,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:sched_debug_start",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/sched/build_utility.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580449963,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468501,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/power/poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/poweroff.c:handle_poweroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470665,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627780901,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510703,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525200,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553861,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559407,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559767,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574395,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:irq_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583416,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811363,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869727,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_handover_do_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872179,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
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
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068556,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
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
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:node_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087926,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429987,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/trace/pid_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/pid_list.c:trace_pid_list_clear",
        "kernel/trace/pid_list.c:trace_pid_list_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453559,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989548,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581993501,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334451,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348013,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582397549,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627843007,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_del_mm",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582589269,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:first_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627843684,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627845261,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627855326,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695332,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582891377,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627868613,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980940,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627874701,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627880969,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150888,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:policy_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596453532,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190916,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234074,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:param_set_sample_interval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627893148,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memory_tier_init",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:next_demotion_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333935,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627894736,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418092,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583693976,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584267754,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584371072,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585670284,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585691176,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585736314,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755272,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586483462,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586502803,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586873399,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_max_workers",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:__io_wq_cpu_online",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160130,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587907242,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_send_component_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020865,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589263953,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265402,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589429153,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628039865,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589473440,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589477214,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589653774,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589700717,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:moom_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940988,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628083776,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171420,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590344228,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628096348,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590724318,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591284958,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592654860,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592679410,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592710216,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593012362,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_parent_cpu_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593574345,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594077573,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595532306,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595738925,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:bsp_pm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595751547,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_distribute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595758496,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595856398,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:165",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
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
  "name": "find_first_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873395,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919843,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:hybrid_format_is_visible",
        "arch/x86/events/intel/core.c:hybrid_tsx_is_visible",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578946549,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971459,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084498,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280865,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330652,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333494,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365969,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373279,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391993,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394561,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409187,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
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
      "addr": 18446744071579427413,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429370,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439494,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461941,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482349,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "addr": 18446744071579492056,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579498360,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501105,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515847,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579542232,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619442541,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606765,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619474487,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725026,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:leave_uniprocessor",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619488293,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619489072,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794533,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799625,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871045,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619521688,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580112537,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207918,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318105,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580377312,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580460243,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:sched_debug_start",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/sched/build_utility.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519995,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580539957,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/power/poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/poweroff.c:handle_poweroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542252,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619543821,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582831,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580627093,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632879,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633239,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580656328,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894506,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953487,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_handover_do_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957584,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158916,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
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
      "addr": 18446744071581179718,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581461197,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526739,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/trace/pid_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/pid_list.c:trace_pid_list_clear",
        "kernel/trace/pid_list.c:trace_pid_list_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551070,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582180876,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184826,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374544,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_empty",
        "kernel/bpf/cpumask.c:bpf_cpumask_first"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535667,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550890,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582603453,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619607503,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_release_memcg",
        "mm/vmscan.c:lru_gen_offline_memcg",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_del_mm",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796629,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:first_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619608180,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619620776,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:page_alloc_init_late",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:early_pfn_to_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619622066,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619631758,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582902134,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/show_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/show_mem.c:__show_free_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909252,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106577,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info",
        "mm/vmalloc.c:vmap_ram_vread_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181460,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583192556,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619639165,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619644137,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583361240,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:policy_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596994861,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408948,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451706,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:param_set_sample_interval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619656076,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memory_tier_init",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:next_demotion_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553503,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619657696,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583638348,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583911864,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584498011,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599392,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585900044,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585921529,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585967079,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585985943,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586731035,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587423314,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588179182,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups",
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588181226,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_send_component_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588295263,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589560749,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589562106,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728305,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619805354,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773134,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589777438,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957916,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590005405,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:moom_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590250271,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619849631,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590485644,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590489890,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590664292,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619862268,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591065646,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635163,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692603,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591742978,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593085628,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593110450,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593147112,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593463914,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_parent_cpu_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594055741,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594457289,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/fec.c:ethtool_link_modes_to_fecparam"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596040652,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596264893,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:bsp_pm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596275851,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_distribute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596282832,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596373278,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_first_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895714,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/core.c:allocate_fake_cpuc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942659,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:hybrid_format_is_visible",
        "arch/x86/events/intel/core.c:hybrid_tsx_is_visible",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969941,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996227,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110290,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310769,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360767,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363612,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397473,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404783,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420747,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579422945,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438140,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
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
      "addr": 18446744071579456997,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458954,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469126,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492005,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579512461,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "addr": 18446744071579522307,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579528200,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531364,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579544567,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579571048,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621738677,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636397,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621770967,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759890,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:leave_uniprocessor",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621784645,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621785888,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579828213,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833341,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908965,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081160,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "addr": 18446744071580157689,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580256238,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370841,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580435310,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519891,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:init_sched_groups_capacity",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/sched/build_utility.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580581319,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580601765,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/power/poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/poweroff.c:handle_poweroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604140,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621842733,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646959,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692149,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698031,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698391,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_needs_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580721544,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621851600,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964117,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984940,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045071,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_handover_do_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049168,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264420,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
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
      "caller_func": []
    },
    {
      "addr": 18446744071581285398,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570452,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638563,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/trace/pid_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/pid_list.c:trace_pid_list_clear",
        "kernel/trace/pid_list.c:trace_pid_list_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663294,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762376,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:parse_pred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582329644,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333594,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541872,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_empty",
        "kernel/bpf/cpumask.c:bpf_cpumask_first"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704482,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721482,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582774909,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621911631,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_release_memcg",
        "mm/vmscan.c:lru_gen_offline_memcg",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_del_mm",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582927815,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/shrinker.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shrinker.c:reparent_shrinker_deferred",
        "mm/shrinker.c:expand_one_shrinker_info",
        "mm/shrinker.c:alloc_shrinker_info",
        "mm/shrinker.c:free_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582971253,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:first_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621912356,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621924920,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:page_alloc_init_late",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:early_pfn_to_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621926210,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621935806,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073638,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/show_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/show_mem.c:show_free_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082148,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583289201,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info",
        "mm/vmalloc.c:vmap_ram_vread_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583365252,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583377652,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388676,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621945357,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494552,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:shrink_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621951609,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:remove_pool_hugetlb_folio",
        "mm/hugetlb.c:alloc_pool_huge_folio",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583597688,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:policy_nodemask",
        "mm/mempolicy.c:interleave_nid",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_preferred",
        "mm/mempolicy.c:mpol_new_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597924349,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645967,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_late",
        "mm/kfence/core.c:kfence_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621961149,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memory_tier_init",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:next_demotion_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742895,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621963680,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833436,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584117688,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584722895,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584831104,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586148508,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586169401,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586215974,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586233271,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587002727,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587758098,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470030,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups",
        "lib/group_cpus.c:grp_spread_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588472106,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/pldmfw/pldmfw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pldmfw/pldmfw.c:pldm_send_component_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588589063,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622096488,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589866442,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/pnp/manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/manager.c:pnp_assign_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589869933,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/pnp/support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/support.c:dbg_pnp_show_option"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589871338,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/pnp/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/interface.c:pnp_print_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590066273,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622113823,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590109190,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590113764,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590295484,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590343837,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:moom_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590591263,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622158463,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590836966,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590840914,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591024868,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622170828,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591410445,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/nvdimm/nd_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592375755,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592435611,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592486562,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593838028,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593863464,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593900920,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/powernow-k8.c:fill_powernow_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594211001,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:get_parent_cpu_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594846237,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
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
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595259561,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/fec.c:ethtool_link_modes_to_fecparam"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596905344,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597147581,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:bsp_pm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597160683,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_distribute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597167419,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597266638,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "find_first_bit",
      "external": false,
      "loc": "include/linux/find.h:200",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
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
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224096,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:98",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/vmalloc.c:s_show",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224096,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159312,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:98",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/vmalloc.c:s_show",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/hv/vmbus_drv.c:vmbus_isr",
        "drivers/hv/channel_mgmt.c:init_vp_index",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159312,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207856,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:98",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/vmalloc.c:s_show",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207856,
      "name": "find_first_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312416,
      "name": "find_first_bit",
      "external": true,
      "loc": "lib/find_bit.c:98",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_arch_events_quirk",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/topology.c:topology_init",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_store",
        "arch/x86/kernel/cpu/cacheinfo.c:subcaches_show",
        "arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/apic.c:setup_local_APIC",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/mm/init_64.c:mem_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:workqueue_init",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/stats.c:schedstat_start",
        "kernel/sched/debug.c:sched_debug_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/isolation.c:bitmap_empty",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/poweroff.c:handle_poweroff",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_do_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device",
        "kernel/cgroup/cgroup.c:cgroup_release",
        "kernel/cgroup/cgroup.c:cgroup_exit",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_print_ss_mask",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:cgroup_migrate_execute",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
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
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_start",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:drop_slab",
        "mm/mmzone.c:first_online_pgdat",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/vmalloc.c:s_show",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:early_pfn_to_nid",
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_preferred",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_new_bind",
        "mm/mempolicy.c:mpol_new_interleave",
        "mm/sparse-vmemmap.c:altmap_alloc_block_buf",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/kcore.c:kcore_update_ram",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_set_bit",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_ord_to_pos",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/pnp/manager.c:pnp_assign_resources",
        "drivers/pnp/support.c:dbg_pnp_show_option",
        "drivers/pnp/interface.c:options_show",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_rebalance",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/sysrq.c:moom_callback",
        "drivers/tty/vt/keyboard.c:do_compute_shiftstate",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/hpet.c:hpet_open",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/cacheinfo.c:cache_default_attrs_is_visible",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/input.c:input_dev_toggle",
        "drivers/input/ff-core.c:input_ff_create",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort",
        "drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_val",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "lib/idr.c:ida_free",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "lib/nodemask.c:__next_node_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312416,
      "name": "find_first_bit",
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
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
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int find_first_bit(const long unsigned int * addr, long unsigned int size)
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

# Function: <code>__bitmap_weight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011952,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:237",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:smp_announce",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:init_workqueues",
        "kernel/pid.c:pidmap_init",
        "kernel/pid.c:pidmap_init",
        "kernel/sched/core.c:sd_degenerate",
        "kernel/sched/core.c:register_sched_domain_sysctl",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/fair.c:get_update_sysctl_factor",
        "kernel/sched/fair.c:update_max_interval",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_announce",
        "kernel/smp.c:smp_init",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_machine",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/trace/trace.c:print_event_info",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/events/core.c:perf_mmap",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_reorder",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/mm_init.c:mm_compute_batch",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/hugetlb.c:hugetlb_init",
        "mm/slub.c:list_locations",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/proc/stat.c:stat_open",
        "block/blk-mq-tag.c:bt_unused_tags",
        "lib/cpumask.c:cpumask_local_spread",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/memweight.c:memweight",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/percpu_counter.c:percpu_counter_startup",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/net/virtio_net.c:virtnet_set_affinity",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer",
        "drivers/cpufreq/cpufreq_governor.c:dbs_timer",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/dev.c:netif_get_num_default_rss_queues",
        "net/core/flow.c:flow_cache_flush",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011952,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302880,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:239",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init",
        "arch/x86/events/intel/uncore.c:uncore_cpu_starting",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:smp_announce",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:_cpu_down",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/pid.c:pidmap_init",
        "kernel/pid.c:pidmap_init",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:sd_degenerate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/nmi.c:printk_nmi_flush_on_panic",
        "kernel/irq/affinity.c:irq_create_affinity_mask",
        "kernel/irq/affinity.c:irq_create_affinity_mask",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_announce",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/trace/trace.c:print_event_info",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/events/core.c:perf_mmap",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/mm_init.c:mm_compute_batch",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/slub.c:list_locations",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/proc/stat.c:stat_open",
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors",
        "block/blk-mq-tag.c:bt_unused_tags",
        "lib/cpumask.c:cpumask_local_spread",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/percpu_counter.c:percpu_counter_startup",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/flow.c:flow_cache_flush",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302880,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583421920,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:239",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/printk/nmi.c:printk_nmi_flush_on_panic",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/trace/trace.c:print_event_info",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_populate",
        "kernel/events/core.c:perf_mmap",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/mm_init.c:mm_compute_batch",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/slub.c:list_locations",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/proc/stat.c:stat_open",
        "lib/cpumask.c:cpumask_local_spread",
        "lib/nodemask.c:node_random",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "lib/percpu_counter.c:percpu_counter_cpu_dead",
        "lib/sbitmap.c:sbitmap_weight",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/md/dm.c:dm_create",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/flow.c:flow_cache_flush",
        "net/core/flow.c:flow_cache_lookup",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583421920,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583442736,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:239",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/kprobes.c:register_kretprobe",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/trace/trace.c:trace_default_header",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate",
        "kernel/events/core.c:perf_mmap",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/mm_init.c:mm_compute_batch",
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/slub.c:list_locations",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/proc/stat.c:stat_open",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "lib/percpu_counter.c:percpu_counter_cpu_dead",
        "lib/sbitmap.c:sbitmap_weight",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/md/dm.c:dm_create",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/flow.c:flow_cache_flush",
        "net/core/flow.c:flow_cache_lookup",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc",
        "lib/cpumask.c:cpumask_local_spread",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442736,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622672,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:241",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/sched/membarrier.c:SyS_membarrier",
        "kernel/sched/membarrier.c:SyS_membarrier",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/kprobes.c:register_kretprobe",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/trace/trace.c:trace_default_header",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate",
        "kernel/events/core.c:perf_mmap",
        "kernel/padata.c:padata_reorder_timer",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/mm_init.c:mm_compute_batch",
        "mm/percpu.c:pcpu_chunk_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint",
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/slub.c:list_locations",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/proc/stat.c:stat_open",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "lib/percpu_counter.c:percpu_counter_cpu_dead",
        "lib/sbitmap.c:sbitmap_weight",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/xen/time.c:xen_manage_runstate_time",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/md/dm.c:dm_create",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc",
        "lib/cpumask.c:cpumask_local_spread",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622672,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583838512,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:238",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/kprobes.c:register_kretprobe",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/trace/trace.c:trace_default_header",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate",
        "kernel/events/core.c:perf_mmap",
        "kernel/padata.c:padata_reorder_timer",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/mm_init.c:mm_compute_batch",
        "mm/percpu.c:pcpu_cnt_pop_pages",
        "mm/percpu.c:pcpu_cnt_pop_pages",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/slub.c:list_locations",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/proc/stat.c:stat_open",
        "security/apparmor/lsm.c:apparmor_init",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "lib/bucket_locks.c:alloc_bucket_spinlocks",
        "lib/percpu_counter.c:percpu_counter_cpu_dead",
        "lib/sbitmap.c:sbitmap_weight",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/xen/time.c:xen_manage_runstate_time",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/net/xen-netfront.c:netif_init",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/md/dm.c:dm_create",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc",
        "lib/cpumask.c:cpumask_local_spread",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838512,
      "name": "__bitmap_weight",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922352,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:235",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/kprobes.c:register_kretprobe",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/trace/trace.c:print_event_info",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate",
        "kernel/events/core.c:perf_mmap",
        "kernel/padata.c:padata_reorder_timer",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/mm_init.c:mm_compute_batch",
        "mm/percpu.c:pcpu_cnt_pop_pages",
        "mm/percpu.c:pcpu_cnt_pop_pages",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/slub.c:list_locations",
        "mm/memory_hotplug.c:add_memory_resource",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/proc/stat.c:stat_open",
        "security/apparmor/lsm.c:alloc_buffers",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/bucket_locks.c:__alloc_bucket_spinlocks",
        "lib/percpu_counter.c:percpu_counter_cpu_dead",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/xen/time.c:xen_manage_runstate_time",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/net/xen-netfront.c:netif_init",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/md/dm.c:dm_create",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc",
        "lib/cpumask.c:cpumask_local_spread",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922352,
      "name": "__bitmap_weight",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102288,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:235",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/page-writeback.c:writeback_set_ratelimit",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "fs/proc/stat.c:stat_open",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/region.c:cpumask_weight",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:dm_get_numa_node",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:cpumask_weight",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102288,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225072,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_next",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_start",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:dm_get_numa_node",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:cpumask_weight",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225072,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630656,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:334",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:cpumask_weight",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:cpumask_weight",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "fs/io-wq.c:io_wq_manager",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_remap",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/nodemask.c:node_random",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630656,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749712,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:334",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:cpumask_weight",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:cpumask_weight",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_remap",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/nodemask.c:node_random",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749712,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778048,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:336",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpumask_weight",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:cpumask_weight",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_remap",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/nodemask.c:node_random",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "drivers/powercap/dtpm_cpu.c:cpumask_weight",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778048,
      "name": "__bitmap_weight",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585208560,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:336",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/hyperv/hv_apic.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpumask_weight",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:cpumask_weight",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:cpumask_weight",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/nodemask.c:node_random",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel/iommu.c:domains_used_show",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "drivers/powercap/dtpm_cpu.c:cpumask_weight",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585208560,
      "name": "__bitmap_weight",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044640,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:336",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/hyperv/hv_apic.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/numa.c:node_set_online",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/build_policy.c:cpumask_weight",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:cpumask_weight",
        "kernel/power/energy_model.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/padata.c:cpumask_weight",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:cpumask_weight",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/nodemask.c:node_random",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel/iommu.c:domains_used_show",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/thermal/intel/intel_hfi.c:cpumask_weight",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044640,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
unsigned int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027568,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:349",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/hyperv/hv_apic.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/build_policy.c:cpumask_weight",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:cpumask_weight",
        "kernel/power/energy_model.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/cgroup/cpuset.c:node_random",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/padata.c:cpumask_weight",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:cpumask_weight",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/memory-tiers.c:next_demotion_node",
        "fs/proc/fd.c:proc_readfd_count",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/char/random.c:cpumask_weight",
        "drivers/iommu/intel/iommu.c:domains_used_show",
        "drivers/iommu/intel/iommu.c:disable_dmar_iommu",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/thermal/intel/intel_hfi.c:cpumask_weight",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027568,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
unsigned int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587282672,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:349",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/hyperv/hv_apic.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/build_policy.c:cpumask_weight",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:cpumask_weight",
        "kernel/power/energy_model.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/padata.c:cpumask_weight",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/page_alloc.c:cpumask_weight",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/memory-tiers.c:next_demotion_node",
        "fs/proc/fd.c:proc_readfd_count",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/group_cpus.c:cpumask_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/char/random.c:cpumask_weight",
        "drivers/iommu/intel/iommu.c:domains_used_show",
        "drivers/iommu/intel/iommu.c:disable_dmar_iommu",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/thermal/intel/intel_hfi.c:cpumask_weight",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282672,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
unsigned int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587570640,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:338",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/hyperv/hv_apic.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:cpumask_weight",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables",
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/sched/core.c:cpumask_weight",
        "kernel/sched/fair.c:cpumask_weight",
        "kernel/sched/build_policy.c:cpumask_weight",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:cpumask_weight",
        "kernel/power/energy_model.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:smp_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/trace/trace_events_filter.c:cpumask_weight",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/cpumask.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/page_alloc.c:cpumask_weight",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_hugetlb_folio",
        "mm/hugetlb.c:alloc_pool_huge_folio",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:interleave_nid",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/memory-tiers.c:next_demotion_node",
        "fs/proc/fd.c:proc_readfd_count",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/group_cpus.c:cpumask_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/char/random.c:cpumask_weight",
        "drivers/iommu/intel/iommu.c:domains_used_show",
        "drivers/iommu/intel/iommu.c:disable_dmar_iommu",
        "drivers/base/cacheinfo.c:cpumask_weight",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/thermal/intel/intel_hfi.c:cpumask_weight",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/core/net-sysfs.c:cpumask_weight",
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587570640,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496099880,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/setup.c:setup_arch",
        "arch/arm64/kernel/smp.c:cpus_are_stuck_in_kernel",
        "arch/arm64/mm/context.c:asids_init",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/mm_init.c:mm_compute_batch",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/hugetlb.c:hugetlb_init",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/bucket_locks.c:__alloc_bucket_spinlocks",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_enable_irqs",
        "drivers/soc/fsl/qbman/qman.c:qman_enable_irqs",
        "drivers/xen/time.c:xen_manage_runstate_time",
        "drivers/base/arch_topology.c:topology_parse_cpu_capacity",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_state2power",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/perf/arm-cci.c:cci_pmu_enable",
        "drivers/perf/arm_pmu.c:cpu_pm_pmu_notify",
        "drivers/perf/arm_pmu.c:armpmu_request_irq",
        "drivers/perf/arm_pmu.c:armpmu_enable",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_enable",
        "drivers/perf/xgene_pmu.c:xgene_perf_pmu_enable",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496099880,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229427000,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/perf/arm-cci.c:cci_pmu_enable",
        "drivers/perf/arm_pmu.c:cpu_pm_pmu_notify",
        "drivers/perf/arm_pmu.c:armpmu_enable",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229427000,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290344576,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/watchdog.c:start_watchdog",
        "arch/powerpc/kernel/watchdog.c:watchdog_timer_fn",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:node_set_online",
        "arch/powerpc/sysdev/mpic.c:smp_mpic_probe",
        "arch/powerpc/sysdev/mpic.c:mpic_alloc",
        "arch/powerpc/sysdev/mpic.c:mpic_alloc",
        "arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask",
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters",
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/xmon/xmon.c:symbol_lookup",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:wait_for_other_cpus",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:cleanup_all_core_imc_memory",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_init",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/mm_init.c:mm_compute_batch",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:add_memory_resource",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "security/apparmor/lsm.c:apparmor_init",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/bucket_locks.c:__alloc_bucket_spinlocks",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_state2power",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power",
        "drivers/md/dm.c:alloc_dev",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290344576,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275169214,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/memweight.c:memweight",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169214,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193808,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free",
        "drivers/md/dm.c:dm_get_numa_node",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:cpumask_weight",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193808,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129024,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/scsi/storvsc_drv.c:cpumask_weight",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free",
        "drivers/md/dm.c:dm_get_numa_node",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "drivers/hv/channel_mgmt.c:cpumask_weight",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:cpumask_weight",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129024,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584177568,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:dm_get_numa_node",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:cpumask_weight",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177568,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __bitmap_weight(const long unsigned int * bitmap, unsigned int bits)
```

```json
{
  "name": "__bitmap_weight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281904,
      "name": "__bitmap_weight",
      "external": true,
      "loc": "lib/bitmap.c:255",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:cpumask_weight",
        "arch/x86/hyperv/mmu.c:cpumask_weight",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/proc.c:cpumask_weight",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight",
        "arch/x86/kernel/smpboot.c:cpumask_weight",
        "arch/x86/kernel/tsc_sync.c:cpumask_weight",
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe",
        "arch/x86/mm/mmio-mod.c:cpumask_weight",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_next",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_start",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/uv_nmi.c:cpumask_weight",
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/rt.c:cpumask_weight",
        "kernel/sched/deadline.c:cpumask_weight",
        "kernel/sched/topology.c:sd_degenerate",
        "kernel/sched/cpufreq_schedutil.c:cpumask_weight",
        "kernel/irq/affinity.c:cpumask_weight",
        "kernel/time/clockevents.c:cpumask_weight",
        "kernel/smp.c:cpumask_weight",
        "kernel/cgroup/cpuset.c:cpumask_weight",
        "kernel/stop_machine.c:cpumask_weight",
        "kernel/padata.c:cpumask_weight",
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/mempolicy.c:mpol_relative_nodemask",
        "lib/bitmap.c:bitmap_bitremap",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_pos_to_ord",
        "lib/memweight.c:memweight",
        "lib/sbitmap.c:__sbitmap_weight",
        "lib/sbitmap.c:__sbitmap_weight",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/md/dm.c:dm_get_numa_node",
        "drivers/cpufreq/cpufreq_governor.c:cpumask_weight",
        "drivers/cpufreq/acpi-cpufreq.c:cpumask_weight",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/net-sysfs.c:cpumask_weight",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281904,
      "name": "__bitmap_weight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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

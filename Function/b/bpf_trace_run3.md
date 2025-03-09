# Function: <code>bpf_trace_run3</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567600,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1135",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/migrate.c:__bpf_trace_mm_numa_migrate_ratelimit",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567600,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625152,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1180",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625152,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685040,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1349",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_power_domain",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_writeback_one",
        "fs/dax.c:__bpf_trace_dax_writeback_range_class",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_insert_range",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_hold",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685040,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732064,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_power_domain",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_writeback_one",
        "fs/dax.c:__bpf_trace_dax_writeback_range_class",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_insert_range",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_hold",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732064,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845104,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1867",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/io_uring.c:__bpf_trace_io_uring_task_run",
        "fs/io_uring.c:__bpf_trace_io_uring_complete",
        "fs/io_uring.c:__bpf_trace_io_uring_link",
        "fs/io_uring.c:__bpf_trace_io_uring_defer",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/intel/trace.c:__bpf_trace_dma_unmap",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845104,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842416,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2123",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/io_uring.c:__bpf_trace_io_uring_task_run",
        "fs/io_uring.c:__bpf_trace_io_uring_complete",
        "fs/io_uring.c:__bpf_trace_io_uring_link",
        "fs/io_uring.c:__bpf_trace_io_uring_defer",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/clk/clk.c:__bpf_trace_clk_rate_range",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/intel/trace.c:__bpf_trace_dma_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842416,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846080,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1819",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/slab_common.c:__bpf_trace_kmem_cache_free",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/io_uring.c:__bpf_trace_io_uring_task_run",
        "fs/io_uring.c:__bpf_trace_io_uring_link",
        "fs/io_uring.c:__bpf_trace_io_uring_defer",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/clk/clk.c:__bpf_trace_clk_rate_range",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846080,
      "name": "bpf_trace_run3",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045872,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1903",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/slab_common.c:__bpf_trace_kmem_cache_free",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/io_uring.c:__bpf_trace_io_uring_link",
        "fs/io_uring.c:__bpf_trace_io_uring_defer",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_iter",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/clk/clk.c:__bpf_trace_clk_rate_range",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_sensorhub_filter",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_qdisc_enqueue",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045872,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302032,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2084",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/module/main.c:__bpf_trace_module_request",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_kmem_cache_free",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock",
        "mm/rmap.c:__bpf_trace_migration_pte",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_iter",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_rq_completion",
        "io_uring/io_uring.c:__bpf_trace_io_uring_link",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/clk/clk.c:__bpf_trace_clk_rate_range",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_qdisc_enqueue",
        "net/core/net-traces.c:__bpf_trace_kfree_skb",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302032,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581627360,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2307",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/module/main.c:__bpf_trace_module_request",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_guest_halt_poll_ns",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_idle_miss",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/trace/rv/rv.c:__bpf_trace_error_da_monitor_id",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_kmem_cache_free",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock",
        "mm/mmap.c:__bpf_trace_vma_mas_szero",
        "mm/rmap.c:__bpf_trace_migration_pte",
        "mm/vmalloc.c:__bpf_trace_free_vmap_area_noflush",
        "mm/vmalloc.c:__bpf_trace_purge_vmap_area_lazy",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_iter",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_rq_completion",
        "io_uring/io_uring.c:__bpf_trace_io_uring_local_work_run",
        "io_uring/io_uring.c:__bpf_trace_io_uring_task_work_run",
        "io_uring/io_uring.c:__bpf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_rate_range",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/scsi/sd_zbc.c:__bpf_trace_scsi_prepare_zone_append",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_set_timeout",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_qdisc_enqueue",
        "net/core/net-traces.c:__bpf_trace_kfree_skb",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627360,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767280,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2316",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_ipi_send_cpumask",
        "kernel/sched/core.c:__bpf_trace_ipi_send_cpu",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/module/main.c:__bpf_trace_module_request",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/trace_osnoise.c:__bpf_trace_sample_threshold",
        "kernel/trace/trace_osnoise.c:__bpf_trace_softirq_noise",
        "kernel/trace/trace_osnoise.c:__bpf_trace_thread_noise",
        "kernel/trace/power-traces.c:__bpf_trace_guest_halt_poll_ns",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_idle_miss",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/trace/rv/rv.c:__bpf_trace_error_da_monitor_id",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_kmem_cache_free",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock",
        "mm/mmap.c:__bpf_trace_vma_mas_szero",
        "mm/rmap.c:__bpf_trace_migration_pte",
        "mm/vmalloc.c:__bpf_trace_free_vmap_area_noflush",
        "mm/vmalloc.c:__bpf_trace_purge_vmap_area_lazy",
        "mm/ksm.c:__bpf_trace_ksm_remove_rmap_item",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_dio_complete",
        "fs/iomap/trace.c:__bpf_trace_iomap_iter",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_rq_completion",
        "io_uring/io_uring.c:__bpf_trace_io_uring_local_work_run",
        "io_uring/io_uring.c:__bpf_trace_io_uring_task_work_run",
        "io_uring/io_uring.c:__bpf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_rate_range",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/scsi/sd_zbc.c:__bpf_trace_scsi_prepare_zone_append",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_set_timeout",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_qdisc_enqueue",
        "net/core/net-traces.c:__bpf_trace_kfree_skb",
        "net/devlink/leftover.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/devlink/leftover.c:__bpf_trace_devlink_hwerr",
        "net/handshake/trace.c:__bpf_trace_handshake_event_class"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767280,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878128,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2421",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_ipi_send_cpumask",
        "kernel/sched/core.c:__bpf_trace_ipi_send_cpu",
        "kernel/sched/core.c:__bpf_trace_sched_skip_vma_numa",
        "kernel/sched/core.c:__bpf_trace_sched_move_numa",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/module/main.c:__bpf_trace_module_request",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/trace_osnoise.c:__bpf_trace_sample_threshold",
        "kernel/trace/trace_osnoise.c:__bpf_trace_softirq_noise",
        "kernel/trace/trace_osnoise.c:__bpf_trace_thread_noise",
        "kernel/trace/power-traces.c:__bpf_trace_guest_halt_poll_ns",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_idle_miss",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/trace/rv/rv.c:__bpf_trace_error_da_monitor_id",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_kmem_cache_free",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock",
        "mm/mmap.c:__bpf_trace_vma_mas_szero",
        "mm/rmap.c:__bpf_trace_migration_pte",
        "mm/vmalloc.c:__bpf_trace_free_vmap_area_noflush",
        "mm/vmalloc.c:__bpf_trace_purge_vmap_area_lazy",
        "mm/ksm.c:__bpf_trace_ksm_advisor",
        "mm/ksm.c:__bpf_trace_ksm_remove_rmap_item",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/iomap/trace.c:__bpf_trace_iomap_dio_complete",
        "fs/iomap/trace.c:__bpf_trace_iomap_iter",
        "fs/iomap/trace.c:__bpf_trace_iomap_range_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_rq_completion",
        "io_uring/io_uring.c:__bpf_trace_io_uring_local_work_run",
        "io_uring/io_uring.c:__bpf_trace_io_uring_task_work_run",
        "io_uring/io_uring.c:__bpf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_rate_range",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/scsi/sd_zbc.c:__bpf_trace_scsi_prepare_zone_append",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_set_timeout",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_qdisc_enqueue",
        "net/core/net-traces.c:__bpf_trace_kfree_skb",
        "net/devlink/core.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/devlink/core.c:__bpf_trace_devlink_hwerr",
        "net/handshake/trace.c:__bpf_trace_handshake_alert_class",
        "net/handshake/trace.c:__bpf_trace_handshake_event_class"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878128,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492048032,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_set_irq",
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_vcpu_wakeup",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_timer_update_irq",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_toggle_cache",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_mmio_emulate",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_exit",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_sys_access",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_hvc_arm64",
        "virt/kvm/arm/vgic/vgic.c:__bpf_trace_vgic_update_irq_pending",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492048032,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225939560,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/dma/tegra20-apb-dma.c:__bpf_trace_tegra_dma_complete_cb",
        "drivers/dma/tegra20-apb-dma.c:__bpf_trace_tegra_dma_tx_status",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/usb/gadget/udc/trace.c:__bpf_trace_udc_log_req",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_jack_report",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_dapm_path",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225939560,
      "name": "bpf_trace_run3",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285210272,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/irq.c:__bpf_trace_hash_fault",
        "arch/powerpc/kernel/irq.c:__bpf_trace_hcall_exit",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_power_domain",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_writeback_one",
        "fs/dax.c:__bpf_trace_dax_writeback_range_class",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_insert_range",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_hold",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285210272,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700864,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_power_domain",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_writeback_one",
        "fs/dax.c:__bpf_trace_dax_writeback_range_class",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_insert_range",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_sq",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_hold",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700864,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647072,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_power_domain",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_writeback_one",
        "fs/dax.c:__bpf_trace_dax_writeback_range_class",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_insert_range",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_sq",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_hold",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647072,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692112,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_power_domain",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_writeback_one",
        "fs/dax.c:__bpf_trace_dax_writeback_range_class",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_insert_range",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_hold",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692112,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```

```json
{
  "name": "bpf_trace_run3",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754480,
      "name": "bpf_trace_run3",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1373",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_setup",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_teardown",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed",
        "arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler",
        "arch/x86/mm/fault.c:__bpf_trace_x86_exceptions",
        "kernel/softirq.c:__bpf_trace_irq_handler_exit",
        "kernel/signal.c:__bpf_trace_signal_deliver",
        "kernel/workqueue.c:__bpf_trace_workqueue_queue_work",
        "kernel/sched/core.c:__bpf_trace_sched_move_task_template",
        "kernel/sched/core.c:__bpf_trace_sched_stat_runtime",
        "kernel/sched/core.c:__bpf_trace_sched_process_exec",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/time/timer.c:__bpf_trace_itimer_expire",
        "kernel/time/timer.c:__bpf_trace_itimer_state",
        "kernel/time/timer.c:__bpf_trace_hrtimer_init",
        "kernel/time/timer.c:__bpf_trace_timer_start",
        "kernel/module.c:__bpf_trace_module_request",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event",
        "kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:__bpf_trace_power_domain",
        "kernel/trace/power-traces.c:__bpf_trace_clock",
        "kernel/trace/power-traces.c:__bpf_trace_suspend_resume",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:__bpf_trace_powernv_throttle",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int",
        "kernel/bpf/core.c:__bpf_trace_xdp_exception",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake",
        "mm/percpu.c:__bpf_trace_percpu_free_percpu",
        "mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/compaction.c:__bpf_trace_kcompactd_wake_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page",
        "mm/page_isolation.c:__bpf_trace_test_pages_isolated",
        "mm/cma.c:__bpf_trace_cma_release",
        "fs/open.c:__bpf_trace_do_sys_open",
        "fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/fs-writeback.c:__bpf_trace_flush_foreign",
        "fs/fs-writeback.c:__bpf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:__bpf_trace_inode_foreign_history",
        "fs/dax.c:__bpf_trace_dax_writeback_one",
        "fs/dax.c:__bpf_trace_dax_writeback_range_class",
        "fs/dax.c:__bpf_trace_dax_insert_mapping",
        "fs/dax.c:__bpf_trace_dax_pte_fault_class",
        "fs/locks.c:__bpf_trace_leases_conflict",
        "fs/locks.c:__bpf_trace_filelock_lock",
        "fs/locks.c:__bpf_trace_locks_get_lock_context",
        "fs/ext4/super.c:__bpf_trace_ext4_error",
        "fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:__bpf_trace_ext4_insert_range",
        "fs/ext4/super.c:__bpf_trace_ext4_collapse_range",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_forget",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_unplug",
        "block/blk-core.c:__bpf_trace_block_get_rq",
        "block/blk-core.c:__bpf_trace_block_bio_merge",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-core.c:__bpf_trace_block_rq_complete",
        "arch/x86/lib/msr.c:__bpf_trace_msr_trace_class",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction",
        "drivers/regulator/core.c:__bpf_trace_regulator_range",
        "drivers/char/random.c:__bpf_trace_urandom_read",
        "drivers/char/random.c:__bpf_trace_push_to_pool",
        "drivers/char/random.c:__bpf_trace_random__mix_pool_bytes",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:__bpf_trace_unmap",
        "drivers/iommu/iommu-traces.c:__bpf_trace_map",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read",
        "drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip",
        "drivers/ras/ras.c:__bpf_trace_memory_failure_event",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_hold",
        "net/core/net-traces.c:__bpf_trace_page_pool_state_release",
        "net/core/net-traces.c:__bpf_trace_inet_sock_set_state",
        "net/core/net-traces.c:__bpf_trace_napi_poll",
        "net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:__bpf_trace_devlink_health_report",
        "net/core/devlink.c:__bpf_trace_devlink_hwerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754480,
      "name": "bpf_trace_run3",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bpf_trace_run3(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2)
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

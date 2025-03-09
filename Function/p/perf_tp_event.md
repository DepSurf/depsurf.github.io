# Function: <code>perf_tp_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_tp_event(u64 addr, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433600,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:6959",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:perf_trace_sys_exit",
        "arch/x86/entry/common.c:perf_trace_sys_enter",
        "arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:perf_trace_xen_mc_entry",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb",
        "arch/x86/xen/trace.c:perf_trace_xen_mc__batch",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_single",
        "arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc",
        "arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_pmd_clear",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_pud_clear",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd_clear",
        "arch/x86/xen/trace.c:perf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry",
        "arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage",
        "arch/x86/xen/trace.c:perf_trace_xen_mc_flush",
        "arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_pte_clear",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_domain_pte",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pgd",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:perf_trace_x86_irq_vector",
        "arch/x86/kernel/nmi.c:perf_trace_nmi_handler",
        "arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record",
        "arch/x86/mm/init.c:perf_trace_tlb_flush",
        "arch/x86/mm/fault.c:perf_trace_x86_exceptions",
        "arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception",
        "arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:perf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx",
        "kernel/fork.c:perf_trace_task_rename",
        "kernel/fork.c:perf_trace_task_newtask",
        "kernel/softirq.c:perf_trace_irq_handler_entry",
        "kernel/softirq.c:perf_trace_softirq",
        "kernel/softirq.c:perf_trace_irq_handler_exit",
        "kernel/signal.c:perf_trace_signal_generate",
        "kernel/signal.c:perf_trace_signal_deliver",
        "kernel/workqueue.c:perf_trace_workqueue_queue_work",
        "kernel/workqueue.c:perf_trace_workqueue_work",
        "kernel/workqueue.c:perf_trace_workqueue_execute_start",
        "kernel/sched/core.c:perf_trace_sched_stat_template",
        "kernel/sched/core.c:perf_trace_sched_wakeup_template",
        "kernel/sched/core.c:perf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:perf_trace_sched_process_wait",
        "kernel/sched/core.c:perf_trace_sched_kthread_stop",
        "kernel/sched/core.c:perf_trace_sched_process_hang",
        "kernel/sched/core.c:perf_trace_sched_stat_runtime",
        "kernel/sched/core.c:perf_trace_sched_process_template",
        "kernel/sched/core.c:perf_trace_sched_pi_setprio",
        "kernel/sched/core.c:perf_trace_sched_migrate_task",
        "kernel/sched/core.c:perf_trace_sched_process_fork",
        "kernel/sched/core.c:perf_trace_sched_switch",
        "kernel/sched/core.c:perf_trace_sched_process_exec",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/printk/printk.c:perf_trace_console",
        "kernel/rcu/update.c:perf_trace_rcu_utilization",
        "kernel/time/timer.c:perf_trace_hrtimer_start",
        "kernel/time/timer.c:perf_trace_itimer_expire",
        "kernel/time/timer.c:perf_trace_hrtimer_class",
        "kernel/time/timer.c:perf_trace_timer_class",
        "kernel/time/timer.c:perf_trace_hrtimer_init",
        "kernel/time/timer.c:perf_trace_timer_expire_entry",
        "kernel/time/timer.c:perf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:perf_trace_timer_start",
        "kernel/time/timer.c:perf_trace_itimer_state",
        "kernel/time/timer.c:perf_trace_tick_stop",
        "kernel/module.c:perf_trace_module_refcnt",
        "kernel/module.c:perf_trace_module_free",
        "kernel/module.c:perf_trace_module_load",
        "kernel/module.c:perf_trace_module_request",
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:perf_trace_cpu",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:perf_trace_suspend_resume",
        "kernel/trace/power-traces.c:perf_trace_pstate_sample",
        "kernel/trace/power-traces.c:perf_trace_wakeup_source",
        "kernel/trace/power-traces.c:perf_trace_clock",
        "kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:perf_trace_power_domain",
        "kernel/trace/power-traces.c:perf_trace_powernv_throttle",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/rpm-traces.c:perf_trace_rpm_return_int",
        "kernel/trace/rpm-traces.c:perf_trace_rpm_internal",
        "mm/filemap.c:perf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:perf_trace_oom_score_adj_update",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_activate",
        "mm/vmscan.c:perf_trace_mm_shrink_slab_start",
        "mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep",
        "mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake",
        "mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd",
        "mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:perf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate_template",
        "mm/vmscan.c:perf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:perf_trace_mm_page",
        "mm/slab_common.c:perf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:perf_trace_mm_page_alloc",
        "mm/slab_common.c:perf_trace_kmem_free",
        "mm/slab_common.c:perf_trace_mm_page_free",
        "mm/slab_common.c:perf_trace_mm_page_free_batched",
        "mm/slab_common.c:perf_trace_kmem_alloc",
        "mm/slab_common.c:perf_trace_kmem_alloc_node",
        "mm/compaction.c:perf_trace_mm_compaction_defer_template",
        "mm/compaction.c:perf_trace_mm_compaction_migratepages",
        "mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:perf_trace_mm_compaction_isolate_template",
        "mm/compaction.c:perf_trace_mm_compaction_begin",
        "mm/compaction.c:perf_trace_mm_compaction_end",
        "mm/compaction.c:perf_trace_mm_compaction_suitable_template",
        "mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit",
        "mm/migrate.c:perf_trace_mm_migrate_pages",
        "mm/cma.c:perf_trace_cma_alloc",
        "mm/cma.c:perf_trace_cma_release",
        "fs/open.c:perf_trace_do_sys_open",
        "fs/open.c:perf_trace_open_exec",
        "fs/fs-writeback.c:perf_trace_writeback_pages_written",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:perf_trace_writeback_lazytime_template",
        "fs/fs-writeback.c:perf_trace_global_dirty_state",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/locks.c:perf_trace_filelock_lease",
        "fs/locks.c:perf_trace_generic_add_lease",
        "fs/ext4/super.c:perf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:perf_trace_ext4__mballoc",
        "fs/ext4/super.c:perf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:perf_trace_ext4_sync_fs",
        "fs/ext4/super.c:perf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:perf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:perf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:perf_trace_ext4_load_inode",
        "fs/ext4/super.c:perf_trace_ext4_journal_start",
        "fs/ext4/super.c:perf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:perf_trace_ext4_request_inode",
        "fs/ext4/super.c:perf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter",
        "fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:perf_trace_ext4_drop_inode",
        "fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:perf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:perf_trace_ext4_evict_inode",
        "fs/ext4/super.c:perf_trace_ext4_collapse_range",
        "fs/ext4/super.c:perf_trace_ext4_insert_range",
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:perf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:perf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:perf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:perf_trace_ext4__truncate",
        "fs/ext4/super.c:perf_trace_ext4__write_end",
        "fs/ext4/super.c:perf_trace_ext4_allocate_inode",
        "fs/ext4/super.c:perf_trace_ext4__write_begin",
        "fs/ext4/super.c:perf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:perf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:perf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:perf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:perf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:perf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:perf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:perf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:perf_trace_ext4__trim",
        "fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:perf_trace_ext4_forget",
        "fs/ext4/super.c:perf_trace_ext4_free_blocks",
        "fs/ext4/super.c:perf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:perf_trace_ext4_find_delalloc_range",
        "fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:perf_trace_ext4__page_op",
        "fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:perf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:perf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:perf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:perf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:perf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:perf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:perf_trace_ext4_writepages_result",
        "fs/ext4/super.c:perf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit",
        "fs/ext4/super.c:perf_trace_ext4__es_extent",
        "fs/ext4/super.c:perf_trace_ext4_da_release_space",
        "fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:perf_trace_ext4_writepages",
        "fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:perf_trace_ext4_request_blocks",
        "fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:perf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:perf_trace_jbd2_run_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:perf_trace_jbd2_checkpoint",
        "fs/jbd2/journal.c:perf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_start",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_extend",
        "fs/jbd2/journal.c:perf_trace_jbd2_commit",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail",
        "fs/jbd2/journal.c:perf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_plug",
        "block/blk-core.c:perf_trace_block_unplug",
        "block/blk-core.c:perf_trace_block_buffer",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_with_error",
        "lib/swiotlb.c:perf_trace_swiotlb_bounced",
        "drivers/gpio/gpiolib.c:perf_trace_gpio_direction",
        "drivers/gpio/gpiolib.c:perf_trace_gpio_value",
        "drivers/regulator/core.c:perf_trace_regulator_range",
        "drivers/regulator/core.c:perf_trace_regulator_basic",
        "drivers/regulator/core.c:perf_trace_regulator_value",
        "drivers/char/random.c:perf_trace_xfer_secondary_pool",
        "drivers/char/random.c:perf_trace_add_input_randomness",
        "drivers/char/random.c:perf_trace_debit_entropy",
        "drivers/char/random.c:perf_trace_add_disk_randomness",
        "drivers/char/random.c:perf_trace_random__get_random_bytes",
        "drivers/char/random.c:perf_trace_add_device_randomness",
        "drivers/char/random.c:perf_trace_urandom_read",
        "drivers/char/random.c:perf_trace_random__mix_pool_bytes",
        "drivers/char/random.c:perf_trace_push_to_pool",
        "drivers/char/random.c:perf_trace_random_read",
        "drivers/char/random.c:perf_trace_random__extract_entropy",
        "drivers/char/random.c:perf_trace_credit_entropy_bits",
        "drivers/iommu/iommu-traces.c:perf_trace_map",
        "drivers/iommu/iommu-traces.c:perf_trace_unmap",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_async",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_reg",
        "drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_bool",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:perf_trace_regcache_sync",
        "drivers/dma-buf/fence.c:perf_trace_fence",
        "drivers/dma-buf/fence.c:perf_trace_fence_annotate_wait_on",
        "drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error",
        "drivers/ata/libata-core.c:perf_trace_ata_qc_issue",
        "drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy",
        "drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template",
        "drivers/spi/spi.c:perf_trace_spi_message_done",
        "drivers/spi/spi.c:perf_trace_spi_master",
        "drivers/spi/spi.c:perf_trace_spi_message",
        "drivers/spi/spi.c:perf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event",
        "drivers/i2c/i2c-core.c:perf_trace_i2c_write",
        "drivers/i2c/i2c-core.c:perf_trace_i2c_result",
        "drivers/i2c/i2c-core.c:perf_trace_smbus_read",
        "drivers/i2c/i2c-core.c:perf_trace_smbus_result",
        "drivers/i2c/i2c-core.c:perf_trace_i2c_read",
        "drivers/i2c/i2c-core.c:perf_trace_smbus_write",
        "drivers/i2c/i2c-core.c:perf_trace_smbus_reply",
        "drivers/i2c/i2c-core.c:perf_trace_i2c_reply",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_cdev_update",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_temperature",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator",
        "drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid",
        "drivers/clk/clk.c:perf_trace_clk_parent",
        "drivers/clk/clk.c:perf_trace_clk",
        "drivers/clk/clk.c:perf_trace_clk_phase",
        "drivers/clk/clk.c:perf_trace_clk_rate",
        "drivers/ras/ras.c:perf_trace_mc_event",
        "drivers/ras/ras.c:perf_trace_memory_failure_event",
        "drivers/ras/ras.c:perf_trace_aer_event",
        "drivers/ras/ras.c:perf_trace_extlog_mem_event",
        "net/core/net-traces.c:perf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:perf_trace_consume_skb",
        "net/core/net-traces.c:perf_trace_kfree_skb",
        "net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:perf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:perf_trace_net_dev_xmit",
        "net/core/net-traces.c:perf_trace_napi_poll",
        "net/core/net-traces.c:perf_trace_net_dev_template",
        "net/core/net-traces.c:perf_trace_fib_table_lookup",
        "net/core/net-traces.c:perf_trace_fib_table_lookup_nh",
        "net/core/net-traces.c:perf_trace_fib_validate_source",
        "net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433600,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463600,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:7571",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463600,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527232,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:7684",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527232,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task, struct perf_event * event)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558528,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:7906",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558528,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580640736,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:7901",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640736,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770544,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8283",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770544,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839072,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8292",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839072,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934048,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8596",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934048,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987984,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987984,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168272,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:9262",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168272,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208208,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:9528",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208208,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224000,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:9658",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224000,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465568,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:9777",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465568,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813920,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:9712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813920,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582241984,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:10113",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241984,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443056,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:10148",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_fprobe.c:fexit_perf_func",
        "kernel/trace/trace_fprobe.c:fentry_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443056,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611232,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:10218",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_fprobe.c:fexit_perf_func",
        "kernel/trace/trace_fprobe.c:fentry_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611232,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492386800,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/events/core.c:perf_trace_run_bpf_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492386800,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226274116,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226274116,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285646336,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285646336,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272456866,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272456866,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956784,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956784,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903792,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903792,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948032,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948032,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void perf_tp_event(u16 event_type, u64 count, void * record, int entry_size, struct pt_regs * regs, struct hlist_head * head, int rctx, struct task_struct * task)
```

```json
{
  "name": "perf_tp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010368,
      "name": "perf_tp_event",
      "external": true,
      "loc": "kernel/events/core.c:8712",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010368,
      "name": "perf_tp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 event_type</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event * event</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct perf_event * event</code>
</li>
</ul>
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

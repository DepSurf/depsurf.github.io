# Function: <code>bpf_trace_run2</code>

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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567520,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1134",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_page",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567520,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625072,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1179",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_page",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625072,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684880,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1348",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/entry/common.c:__bpf_trace_sys_exit",
        "arch/x86/entry/common.c:__bpf_trace_sys_enter",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_pi_setprio",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_generic_add_lease",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_shutdown",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_release_space",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_fs",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:__bpf_trace_ext4_drop_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_queue",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_random__get_random_bytes",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_start",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_probe",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684880,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731904,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/entry/common.c:__bpf_trace_sys_exit",
        "arch/x86/entry/common.c:__bpf_trace_sys_enter",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_pi_setprio",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_generic_add_lease",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_shutdown",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_release_space",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_fs",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:__bpf_trace_ext4_drop_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_queue",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_random__get_random_bytes",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_start",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_probe",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731904,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844944,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1866",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/io_uring.c:__bpf_trace_io_uring_fail_link",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844944,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842256,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2122",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/io_uring.c:__bpf_trace_io_uring_fail_link",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842256,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845920,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1818",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_overutilized_tp",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/rcu/update.c:__bpf_trace_rcu_stall_warning",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/error_report-traces.c:__bpf_trace_error_report_template",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kfree",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages_start",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/io_uring.c:__bpf_trace_io_uring_fail_link",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845920,
      "name": "bpf_trace_run2",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045728,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1902",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_overutilized_tp",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/rcu/update.c:__bpf_trace_rcu_stall_warning",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/error_report-traces.c:__bpf_trace_error_report_template",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kfree",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages_start",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/io_uring.c:__bpf_trace_io_uring_fail_link",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/spi/spi.c:__bpf_trace_spi_set_cs",
        "drivers/spi/spi.c:__bpf_trace_spi_setup",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045728,
      "name": "bpf_trace_run2",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301856,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2083",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_overutilized_tp",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_begin",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/rcu/update.c:__bpf_trace_rcu_stall_warning",
        "kernel/module/main.c:__bpf_trace_module_refcnt",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/error_report-traces.c:__bpf_trace_error_report_template",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kfree",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "mm/rmap.c:__bpf_trace_mm_migrate_pages_start",
        "mm/rmap.c:__bpf_trace_tlb_flush",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "io_uring/io_uring.c:__bpf_trace_io_uring_cqring_wait",
        "drivers/pwm/core.c:__bpf_trace_pwm",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status",
        "drivers/ata/libata-core.c:__bpf_trace_ata_tf_load",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/spi/spi.c:__bpf_trace_spi_set_cs",
        "drivers/spi/spi.c:__bpf_trace_spi_setup",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_tcp_cong_state_set",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301856,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581627136,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2306",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_overutilized_tp",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_begin",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/rcu/update.c:__bpf_trace_rcu_stall_warning",
        "kernel/module/main.c:__bpf_trace_module_refcnt",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/error_report-traces.c:__bpf_trace_error_report_template",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kfree",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/mmap.c:__bpf_trace_vma_store",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "mm/rmap.c:__bpf_trace_mm_migrate_pages_start",
        "mm/rmap.c:__bpf_trace_tlb_flush",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "io_uring/io_uring.c:__bpf_trace_io_uring_submit_sqe",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status",
        "drivers/ata/libata-core.c:__bpf_trace_ata_tf_load",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/spi/spi.c:__bpf_trace_spi_set_cs",
        "drivers/spi/spi.c:__bpf_trace_spi_setup",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_template",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_tcp_cong_state_set",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627136,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767056,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2315",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_tasklet",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_overutilized_tp",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_begin",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/rcu/update.c:__bpf_trace_rcu_stall_warning",
        "kernel/module/main.c:__bpf_trace_module_refcnt",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/smp.c:__bpf_trace_csd_function",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/trace_osnoise.c:__bpf_trace_nmi_noise",
        "kernel/trace/error_report-traces.c:__bpf_trace_error_report_template",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kfree",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/mmap.c:__bpf_trace_vma_store",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "mm/rmap.c:__bpf_trace_mm_migrate_pages_start",
        "mm/rmap.c:__bpf_trace_tlb_flush",
        "mm/ksm.c:__bpf_trace_ksm_scan_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status",
        "drivers/ata/libata-core.c:__bpf_trace_ata_tf_load",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/spi/spi.c:__bpf_trace_spi_set_cs",
        "drivers/spi/spi.c:__bpf_trace_spi_setup",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_template",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_tcp_cong_state_set",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767056,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888320,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2420",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_tasklet",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_end",
        "kernel/sched/core.c:__bpf_trace_sched_overutilized_tp",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_end",
        "kernel/locking/mutex.c:__bpf_trace_contention_begin",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/rcu/update.c:__bpf_trace_rcu_stall_warning",
        "kernel/module/main.c:__bpf_trace_module_refcnt",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_base_idle",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/smp.c:__bpf_trace_csd_function",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/trace_osnoise.c:__bpf_trace_nmi_noise",
        "kernel/trace/error_report-traces.c:__bpf_trace_error_report_template",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_rss_stat",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kfree",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "mm/compaction.c:__bpf_trace_mm_compaction_migratepages",
        "mm/mmap.c:__bpf_trace_vma_store",
        "mm/mmap.c:__bpf_trace_vm_unmapped_area",
        "mm/rmap.c:__bpf_trace_mm_migrate_pages_start",
        "mm/rmap.c:__bpf_trace_tlb_flush",
        "mm/ksm.c:__bpf_trace_ksm_scan_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/iomap/trace.c:__bpf_trace_iomap_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_readpage_class",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_split",
        "block/blk-core.c:__bpf_trace_block_bio_complete",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status",
        "drivers/ata/libata-core.c:__bpf_trace_ata_tf_load",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/spi/spi.c:__bpf_trace_spi_set_cs",
        "drivers/spi/spi.c:__bpf_trace_spi_setup",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_doorbell",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_template",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end",
        "net/core/net-traces.c:__bpf_trace_tcp_cong_state_set",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_release",
        "net/handshake/trace.c:__bpf_trace_tls_contenttype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888320,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492047848,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/arm64/kernel/smp.c:__bpf_trace_ipi_raise",
        "arch/arm64/kernel/armv8_deprecated.c:__bpf_trace_instruction_emulation",
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_ack_irq",
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_userspace_exit",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_timer_emulate",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_get_timer_map",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_set_way_flush",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_arm_set_dreg32",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_wfx_arm64",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492047848,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225939288,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/arm/kernel/ptrace.c:__bpf_trace_sys_enter",
        "arch/arm/kernel/smp.c:__bpf_trace_ipi_raise",
        "arch/arm/common/bL_switcher.c:__bpf_trace_cpu_migrate",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/dma/tegra20-apb-dma.c:__bpf_trace_tegra_dma_isr",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/usb/musb/musb_trace.c:__bpf_trace_musb_urb",
        "drivers/usb/musb/musb_trace.c:__bpf_trace_musb_log",
        "drivers/usb/gadget/udc/trace.c:__bpf_trace_udc_log_ep",
        "drivers/usb/gadget/udc/trace.c:__bpf_trace_udc_log_gadget",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_start",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_jack_notify",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_dapm_connected",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_dapm_widget",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_card",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225939288,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285210032,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/powerpc/kernel/ptrace.c:__bpf_trace_sys_exit",
        "arch/powerpc/kernel/ptrace.c:__bpf_trace_sys_enter",
        "arch/powerpc/kernel/irq.c:__bpf_trace_opal_exit",
        "arch/powerpc/kernel/irq.c:__bpf_trace_opal_entry",
        "arch/powerpc/kernel/irq.c:__bpf_trace_hcall_entry",
        "arch/powerpc/mm/book3s64/hash_pgtable.c:__bpf_trace_hugepage_splitting",
        "arch/powerpc/mm/book3s64/hash_pgtable.c:__bpf_trace_hugepage_set_pmd",
        "arch/powerpc/mm/book3s64/hash_pgtable.c:__bpf_trace_hugepage_invalidate",
        "arch/powerpc/platforms/powernv/vas-window.c:__bpf_trace_vas_paste_crb",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_pi_setprio",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_generic_add_lease",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_shutdown",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_release_space",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_fs",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:__bpf_trace_ext4_drop_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_queue",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_random__get_random_bytes",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_start",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_probe",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285210032,
      "name": "bpf_trace_run2",
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700704,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/entry/common.c:__bpf_trace_sys_exit",
        "arch/x86/entry/common.c:__bpf_trace_sys_enter",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_pi_setprio",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_generic_add_lease",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_shutdown",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_release_space",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_fs",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:__bpf_trace_ext4_drop_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_queue",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_random__get_random_bytes",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_async_event",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_setup_cmd",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_start",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_probe",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700704,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646912,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/entry/common.c:__bpf_trace_sys_exit",
        "arch/x86/entry/common.c:__bpf_trace_sys_enter",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_pi_setprio",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_generic_add_lease",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_shutdown",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_release_space",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_fs",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:__bpf_trace_ext4_drop_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_queue",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_random__get_random_bytes",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_async_event",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_setup_cmd",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_send_tl_connect_request",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_release_relid",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_negotiate_version",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_teardown_gpadl",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_establish_gpadl_body",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_establish_gpadl_header",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_close_internal",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_open",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_probe",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646912,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691952,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/entry/common.c:__bpf_trace_sys_exit",
        "arch/x86/entry/common.c:__bpf_trace_sys_enter",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_pi_setprio",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_generic_add_lease",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_shutdown",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_release_space",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_fs",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:__bpf_trace_ext4_drop_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_queue",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_random__get_random_bytes",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_start",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_probe",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691952,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
```

```json
{
  "name": "bpf_trace_run2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754288,
      "name": "bpf_trace_run2",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_finish",
        "arch/x86/entry/common.c:__bpf_trace_sys_exit",
        "arch/x86/entry/common.c:__bpf_trace_sys_enter",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping",
        "arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_reserve",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2",
        "arch/x86/mm/init.c:__bpf_trace_tlb_flush",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception",
        "kernel/fork.c:__bpf_trace_task_rename",
        "kernel/fork.c:__bpf_trace_task_newtask",
        "kernel/softirq.c:__bpf_trace_irq_handler_entry",
        "kernel/sched/core.c:__bpf_trace_sched_pi_setprio",
        "kernel/sched/core.c:__bpf_trace_sched_stat_template",
        "kernel/sched/core.c:__bpf_trace_sched_process_fork",
        "kernel/sched/core.c:__bpf_trace_sched_migrate_task",
        "kernel/printk/printk.c:__bpf_trace_console",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update",
        "kernel/time/timer.c:__bpf_trace_tick_stop",
        "kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:__bpf_trace_hrtimer_start",
        "kernel/time/timer.c:__bpf_trace_timer_expire_entry",
        "kernel/time/alarmtimer.c:__bpf_trace_alarm_class",
        "kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend",
        "kernel/module.c:__bpf_trace_module_refcnt",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/trace/power-traces.c:__bpf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_wakeup_source",
        "kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:__bpf_trace_cpu",
        "kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal",
        "kernel/bpf/core.c:__bpf_trace_mem_return_failed",
        "kernel/bpf/core.c:__bpf_trace_mem_connect",
        "mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:__bpf_trace_filemap_set_wb_err",
        "mm/swap.c:__bpf_trace_mm_lru_insertion",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:__bpf_trace_mm_page_free",
        "mm/slab_common.c:__bpf_trace_kmem_free",
        "mm/compaction.c:__bpf_trace_mm_compaction_defer_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:__bpf_trace_global_dirty_state",
        "fs/fs-writeback.c:__bpf_trace_wbc_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_work_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:__bpf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_page_template",
        "fs/locks.c:__bpf_trace_generic_add_lease",
        "fs/locks.c:__bpf_trace_filelock_lease",
        "fs/ext4/super.c:__bpf_trace_ext4_shutdown",
        "fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__es_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:__bpf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:__bpf_trace_ext4_da_release_space",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_fs",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages",
        "fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:__bpf_trace_ext4_drop_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_request_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_commit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint",
        "block/blk-core.c:__bpf_trace_block_bio_queue",
        "block/blk-core.c:__bpf_trace_block_bio_bounce",
        "block/blk-core.c:__bpf_trace_block_rq",
        "block/blk-core.c:__bpf_trace_block_rq_requeue",
        "block/blk-wbt.c:__bpf_trace_wbt_lat",
        "block/blk-wbt.c:__bpf_trace_wbt_stat",
        "drivers/clk/clk.c:__bpf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:__bpf_trace_clk_phase",
        "drivers/clk/clk.c:__bpf_trace_clk_parent",
        "drivers/clk/clk.c:__bpf_trace_clk_rate",
        "drivers/regulator/core.c:__bpf_trace_regulator_value",
        "drivers/char/random.c:__bpf_trace_random__get_random_bytes",
        "drivers/char/random.c:__bpf_trace_add_disk_randomness",
        "drivers/char/random.c:__bpf_trace_debit_entropy",
        "drivers/char/random.c:__bpf_trace_add_device_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error",
        "drivers/spi/spi.c:__bpf_trace_spi_transfer",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb",
        "drivers/rtc/interface.c:__bpf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_cdev_update",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:__bpf_trace_mmc_request_start",
        "net/core/net-traces.c:__bpf_trace_neigh__update",
        "net/core/net-traces.c:__bpf_trace_fdb_delete",
        "net/core/net-traces.c:__bpf_trace_tcp_probe",
        "net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:__bpf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:__bpf_trace_kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754288,
      "name": "bpf_trace_run2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
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
void bpf_trace_run2(struct bpf_prog * prog, u64 arg0, u64 arg1)
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

# Function: <code>bpf_trace_run1</code>

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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567440,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1133",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc__batch",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mcheck/mce.c:__bpf_trace_mce_record",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567440,
      "name": "bpf_trace_run1",
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624992,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1178",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc__batch",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624992,
      "name": "bpf_trace_run1",
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684720,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1347",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_one_user",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry_alloc",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc__batch",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_start",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:__bpf_trace_sched_process_hang",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_process_template",
        "kernel/sched/core.c:__bpf_trace_sched_wakeup_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_free",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_skip_task_reaping",
        "mm/oom_kill.c:__bpf_trace_finish_task_reaping",
        "mm/oom_kill.c:__bpf_trace_start_task_reaping",
        "mm/oom_kill.c:__bpf_trace_wake_reaper",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_destroy_chunk",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_load_inode",
        "fs/ext4/super.c:__bpf_trace_ext4__truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:__bpf_trace_ext4_evict_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message_done",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_cmd_class",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684720,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731744,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_one_user",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry_alloc",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc__batch",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_start",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:__bpf_trace_sched_process_hang",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_process_template",
        "kernel/sched/core.c:__bpf_trace_sched_wakeup_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_free",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_skip_task_reaping",
        "mm/oom_kill.c:__bpf_trace_finish_task_reaping",
        "mm/oom_kill.c:__bpf_trace_start_task_reaping",
        "mm/oom_kill.c:__bpf_trace_wake_reaper",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_destroy_chunk",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_load_inode",
        "fs/ext4/super.c:__bpf_trace_ext4__truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:__bpf_trace_ext4_evict_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message_done",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_cmd_class",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731744,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844784,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1865",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844784,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842080,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2121",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/bpf_trace.c:__bpf_trace_bpf_trace_printk",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_prandom_u32",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842080,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845760,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1817",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/bpf_trace.c:__bpf_trace_bpf_trace_printk",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_prandom_u32",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/netlink/af_netlink.c:__bpf_trace_netlink_extack",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845760,
      "name": "bpf_trace_run1",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045568,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1901",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/bpf_trace.c:__bpf_trace_bpf_trace_printk",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_prandom_u32",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/netlink/af_netlink.c:__bpf_trace_netlink_extack",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045568,
      "name": "bpf_trace_run1",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301664,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2082",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/bpf_trace.c:__bpf_trace_bpf_trace_printk",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_write_folio",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/netlink/af_netlink.c:__bpf_trace_netlink_extack",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301664,
      "name": "bpf_trace_run1",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626864,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2305",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/bpf_trace.c:__bpf_trace_bpf_trace_printk",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_write_folio",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "mm/mmap.c:__bpf_trace_exit_mmap",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "io_uring/io_uring.c:__bpf_trace_io_uring_defer",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/netlink/af_netlink.c:__bpf_trace_netlink_extack",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626864,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766784,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2314",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/notifier.c:__bpf_trace_notifier_info",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/bpf_trace.c:__bpf_trace_bpf_trace_printk",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_write_folio",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "mm/mmap.c:__bpf_trace_exit_mmap",
        "mm/ksm.c:__bpf_trace_ksm_remove_ksm_page",
        "mm/ksm.c:__bpf_trace_ksm_enter_exit_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/netlink/af_netlink.c:__bpf_trace_netlink_extack",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766784,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888048,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2419",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/notifier.c:__bpf_trace_notifier_info",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/bpf_trace.c:__bpf_trace_bpf_trace_printk",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_latency_qos_request",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/context_tracking.c:__bpf_trace_context_tracking_user",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_write_folio",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "mm/mmap.c:__bpf_trace_exit_mmap",
        "mm/ksm.c:__bpf_trace_ksm_remove_ksm_page",
        "mm/ksm.c:__bpf_trace_ksm_enter_exit_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_start",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/netlink/af_netlink.c:__bpf_trace_netlink_extack",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish",
        "net/mctp/af_mctp.c:__bpf_trace_mctp_key_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888048,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492047664,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/arm64/kernel/smp.c:__bpf_trace_ipi_handler",
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_fpu",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_handle_sys_reg",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_arm_clear_debug",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_cmd_class",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492047664,
      "name": "bpf_trace_run1",
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225939024,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/arm/kernel/smp.c:__bpf_trace_ipi_handler",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/usb/musb/musb_trace.c:__bpf_trace_musb_req",
        "drivers/usb/musb/musb_trace.c:__bpf_trace_musb_isr",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_cmd_class",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_jack_irq",
        "sound/soc/soc-core.c:__bpf_trace_snd_soc_dapm_basic",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225939024,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285209792,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/powerpc/kernel/irq.c:__bpf_trace_tlbia",
        "arch/powerpc/kernel/irq.c:__bpf_trace_ppc64_interrupt_class",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_start",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:__bpf_trace_sched_process_hang",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_process_template",
        "kernel/sched/core.c:__bpf_trace_sched_wakeup_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_free",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_skip_task_reaping",
        "mm/oom_kill.c:__bpf_trace_finish_task_reaping",
        "mm/oom_kill.c:__bpf_trace_start_task_reaping",
        "mm/oom_kill.c:__bpf_trace_wake_reaper",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_destroy_chunk",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_load_inode",
        "fs/ext4/super.c:__bpf_trace_ext4__truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:__bpf_trace_ext4_evict_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message_done",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285209792,
      "name": "bpf_trace_run1",
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700544,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_one_user",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry_alloc",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc__batch",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_start",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:__bpf_trace_sched_process_hang",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_process_template",
        "kernel/sched/core.c:__bpf_trace_sched_wakeup_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_free",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_skip_task_reaping",
        "mm/oom_kill.c:__bpf_trace_finish_task_reaping",
        "mm/oom_kill.c:__bpf_trace_start_task_reaping",
        "mm/oom_kill.c:__bpf_trace_wake_reaper",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_destroy_chunk",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_load_inode",
        "fs/ext4/super.c:__bpf_trace_ext4__truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:__bpf_trace_ext4_evict_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_complete_rq",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message_done",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_cmd_class",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700544,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646752,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_start",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:__bpf_trace_sched_process_hang",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_process_template",
        "kernel/sched/core.c:__bpf_trace_sched_wakeup_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_free",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/context_tracking.c:__bpf_trace_context_tracking_user",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_skip_task_reaping",
        "mm/oom_kill.c:__bpf_trace_finish_task_reaping",
        "mm/oom_kill.c:__bpf_trace_start_task_reaping",
        "mm/oom_kill.c:__bpf_trace_wake_reaper",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_destroy_chunk",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_load_inode",
        "fs/ext4/super.c:__bpf_trace_ext4__truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:__bpf_trace_ext4_evict_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/nvme/host/core.c:__bpf_trace_nvme_complete_rq",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message_done",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_channel",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_request_offers",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_onversion_response",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_ongpadl_torndown",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_ongpadl_created",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_onopen_result",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_onoffer_rescind",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_onoffer",
        "drivers/hv/hv_trace.c:__bpf_trace_vmbus_hdr_msg",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646752,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691792,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_one_user",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry_alloc",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc__batch",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_start",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:__bpf_trace_sched_process_hang",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_process_template",
        "kernel/sched/core.c:__bpf_trace_sched_wakeup_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_free",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_skip_task_reaping",
        "mm/oom_kill.c:__bpf_trace_finish_task_reaping",
        "mm/oom_kill.c:__bpf_trace_start_task_reaping",
        "mm/oom_kill.c:__bpf_trace_wake_reaper",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_destroy_chunk",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_load_inode",
        "fs/ext4/super.c:__bpf_trace_ext4__truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:__bpf_trace_ext4_evict_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message_done",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_cmd_class",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691792,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
```

```json
{
  "name": "bpf_trace_run1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754096,
      "name": "bpf_trace_run1",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1371",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:__bpf_trace_initcall_start",
        "init/main.c:__bpf_trace_initcall_level",
        "arch/x86/entry/vsyscall/vsyscall_64.c:__bpf_trace_emulate_vsyscall",
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_load_idt",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_one_user",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush_reason",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry_alloc",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mc__batch",
        "arch/x86/kernel/irq.c:__bpf_trace_x86_irq_vector",
        "arch/x86/kernel/fpu/core.c:__bpf_trace_x86_fpu",
        "arch/x86/kernel/cpu/mce/core.c:__bpf_trace_mce_record",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_mem_latency",
        "arch/x86/mm/mpx.c:__bpf_trace_mpx_new_bounds_table",
        "arch/x86/mm/mpx.c:__bpf_trace_bounds_exception_mpx",
        "kernel/softirq.c:__bpf_trace_softirq",
        "kernel/workqueue.c:__bpf_trace_workqueue_execute_start",
        "kernel/workqueue.c:__bpf_trace_workqueue_work",
        "kernel/sched/core.c:__bpf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:__bpf_trace_sched_process_hang",
        "kernel/sched/core.c:__bpf_trace_sched_process_wait",
        "kernel/sched/core.c:__bpf_trace_sched_process_template",
        "kernel/sched/core.c:__bpf_trace_sched_wakeup_template",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:__bpf_trace_sched_kthread_stop",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_global",
        "kernel/rcu/update.c:__bpf_trace_rcu_utilization",
        "kernel/time/timer.c:__bpf_trace_hrtimer_class",
        "kernel/time/timer.c:__bpf_trace_timer_class",
        "kernel/module.c:__bpf_trace_module_free",
        "kernel/module.c:__bpf_trace_module_load",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_root",
        "kernel/trace/power-traces.c:__bpf_trace_cpu_frequency_limits",
        "kernel/bpf/core.c:__bpf_trace_mem_disconnect",
        "kernel/rseq.c:__bpf_trace_rseq_update",
        "mm/filemap.c:__bpf_trace_mm_filemap_op_page_cache",
        "mm/oom_kill.c:__bpf_trace_skip_task_reaping",
        "mm/oom_kill.c:__bpf_trace_finish_task_reaping",
        "mm/oom_kill.c:__bpf_trace_start_task_reaping",
        "mm/oom_kill.c:__bpf_trace_wake_reaper",
        "mm/oom_kill.c:__bpf_trace_mark_victim",
        "mm/oom_kill.c:__bpf_trace_oom_score_adj_update",
        "mm/swap.c:__bpf_trace_mm_lru_activate",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_sleep",
        "mm/percpu.c:__bpf_trace_percpu_destroy_chunk",
        "mm/percpu.c:__bpf_trace_percpu_create_chunk",
        "mm/slab_common.c:__bpf_trace_mm_page_free_batched",
        "mm/compaction.c:__bpf_trace_mm_compaction_kcompactd_sleep",
        "fs/open.c:__bpf_trace_open_exec",
        "fs/fs-writeback.c:__bpf_trace_writeback_inode_template",
        "fs/fs-writeback.c:__bpf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:__bpf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:__bpf_trace_writeback_class",
        "fs/fs-writeback.c:__bpf_trace_writeback_pages_written",
        "fs/ext4/super.c:__bpf_trace_ext4_load_inode",
        "fs/ext4/super.c:__bpf_trace_ext4__truncate",
        "fs/ext4/super.c:__bpf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:__bpf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_request_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:__bpf_trace_ext4__page_op",
        "fs/ext4/super.c:__bpf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:__bpf_trace_ext4_evict_inode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_inode",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_submit_inode_data",
        "block/blk-core.c:__bpf_trace_block_plug",
        "block/blk-core.c:__bpf_trace_block_buffer",
        "drivers/clk/clk.c:__bpf_trace_clk",
        "drivers/regulator/core.c:__bpf_trace_regulator_basic",
        "drivers/char/random.c:__bpf_trace_add_input_randomness",
        "drivers/iommu/iommu-traces.c:__bpf_trace_iommu_device_event",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_async",
        "drivers/dma-buf/dma-fence.c:__bpf_trace_dma_fence",
        "drivers/dma-buf/sw_sync.c:__bpf_trace_sync_timeline",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:__bpf_trace_ata_qc_issue",
        "drivers/spi/spi.c:__bpf_trace_spi_message_done",
        "drivers/spi/spi.c:__bpf_trace_spi_message",
        "drivers/spi/spi.c:__bpf_trace_spi_controller",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_msg",
        "drivers/rtc/interface.c:__bpf_trace_rtc_timer_class",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_temperature",
        "drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_cmd_class",
        "drivers/devfreq/devfreq.c:__bpf_trace_devfreq_monitor",
        "drivers/ras/ras.c:__bpf_trace_arm_event",
        "net/core/net-traces.c:__bpf_trace_tcp_event_sk",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:__bpf_trace_net_dev_template",
        "net/core/net-traces.c:__bpf_trace_consume_skb",
        "net/bpf/test_run.c:__bpf_trace_bpf_test_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754096,
      "name": "bpf_trace_run1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
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
void bpf_trace_run1(struct bpf_prog * prog, u64 arg0)
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

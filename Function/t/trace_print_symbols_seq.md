# Function: <code>trace_print_symbols_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580236240,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:101",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_write",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_result",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236240,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273456,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:101",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273456,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316672,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:101",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "lib/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316672,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329792,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:102",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_next_key",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_delete_elem",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_keyval",
        "kernel/bpf/core.c:trace_raw_output_bpf_obj_map",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_create",
        "kernel/bpf/core.c:trace_raw_output_bpf_prog_load",
        "kernel/bpf/core.c:trace_raw_output_bpf_prog_event",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "lib/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329792,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580383344,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:102",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_next_key",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_delete_elem",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_keyval",
        "kernel/bpf/core.c:trace_raw_output_bpf_obj_map",
        "kernel/bpf/core.c:trace_raw_output_bpf_map_create",
        "kernel/bpf/core.c:trace_raw_output_bpf_prog_load",
        "kernel/bpf/core.c:trace_raw_output_bpf_prog_event",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "lib/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_tcp_set_state",
        "net/core/net-traces.c:trace_raw_output_tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383344,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445328,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:102",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445328,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500992,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500992,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557600,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557600,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605184,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605184,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703680,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703680,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692976,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692976,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697168,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/error_report-traces.c:trace_raw_output_error_report_template",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/slab_common.c:trace_raw_output_rss_stat",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages_start",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages_start",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "drivers/iommu/intel/trace.c:trace_raw_output_qi_submit",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_probe",
        "net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit",
        "net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697168,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874256,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/error_report-traces.c:trace_raw_output_error_report_template",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/slab_common.c:trace_raw_output_rss_stat",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages_start",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages_start",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "drivers/iommu/intel/trace.c:trace_raw_output_qi_submit",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_probe",
        "net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit",
        "net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874256,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104912,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:104",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/error_report-traces.c:trace_raw_output_error_report_template",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/slab_common.c:trace_raw_output_rss_stat",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_tlb_flush",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "drivers/iommu/intel/trace.c:trace_raw_output_qi_submit",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_probe",
        "net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_raw_output_kfree_skb",
        "net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail",
        "net/mctp/af_mctp.c:trace_raw_output_mctp_key_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104912,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413520,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/error_report-traces.c:trace_raw_output_error_report_template",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/slab_common.c:trace_raw_output_rss_stat",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_tlb_flush",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_collapse_file",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_file",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "drivers/iommu/intel/trace.c:trace_raw_output_qi_submit",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_probe",
        "net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_raw_output_kfree_skb",
        "net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail",
        "net/mctp/af_mctp.c:trace_raw_output_mctp_key_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413520,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508656,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/trace_osnoise.c:trace_raw_output_softirq_noise",
        "kernel/trace/error_report-traces.c:trace_raw_output_error_report_template",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/slab_common.c:trace_raw_output_rss_stat",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_tlb_flush",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_collapse_file",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_file",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "drivers/iommu/intel/trace.c:trace_raw_output_qi_submit",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_cong_state_set",
        "net/core/net-traces.c:trace_raw_output_tcp_probe",
        "net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_sock_msg_length",
        "net/core/net-traces.c:trace_raw_output_sock_msg_length",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_raw_output_kfree_skb",
        "net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail",
        "net/mctp/af_mctp.c:trace_raw_output_mctp_key_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508656,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620192,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/sched/core.c:trace_raw_output_sched_skip_vma_numa",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/trace_osnoise.c:trace_raw_output_softirq_noise",
        "kernel/trace/error_report-traces.c:trace_raw_output_error_report_template",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/slab_common.c:trace_raw_output_rss_stat",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages_start",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_mm_migrate_pages",
        "mm/rmap.c:trace_raw_output_tlb_flush",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_collapse_file",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_file",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_fc_stats",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "drivers/iommu/intel/trace.c:trace_raw_output_qi_submit",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_tf_load",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_cong_state_set",
        "net/core/net-traces.c:trace_raw_output_tcp_probe",
        "net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_sock_msg_length",
        "net/core/net-traces.c:trace_raw_output_sock_msg_length",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sk_error_report",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit",
        "net/core/net-traces.c:trace_raw_output_kfree_skb",
        "net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail",
        "net/mctp/af_mctp.c:trace_raw_output_mctp_key_release",
        "net/handshake/trace.c:trace_raw_output_tls_contenttype",
        "net/handshake/trace.c:trace_raw_output_handshake_alert_class",
        "net/handshake/trace.c:trace_raw_output_handshake_alert_class"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620192,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491904504,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:trace_raw_output_kvm_fpu",
        "virt/kvm/kvm_main.c:trace_raw_output_kvm_mmio",
        "virt/kvm/kvm_main.c:trace_raw_output_kvm_userspace_exit",
        "virt/kvm/arm/arm.c:trace_raw_output_kvm_exit",
        "virt/kvm/arm/arm.c:trace_raw_output_kvm_exit",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491904504,
      "name": "trace_print_symbols_seq",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225846388,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225846388,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284992640,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284992640,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272191512,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272191512,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573984,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_async_event",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573984,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580520608,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_async_event",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd",
        "drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520608,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565232,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565232,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
const char * trace_print_symbols_seq(struct trace_seq * p, long unsigned int val, const struct trace_print_flags * symbol_array)
```

```json
{
  "name": "trace_print_symbols_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621952,
      "name": "trace_print_symbols_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:103",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:trace_raw_output_tlb_flush",
        "kernel/softirq.c:trace_raw_output_softirq",
        "kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced",
        "kernel/time/timer.c:trace_raw_output_tick_stop",
        "kernel/time/timer.c:trace_raw_output_hrtimer_start",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/time/timer.c:trace_raw_output_hrtimer_init",
        "kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:trace_raw_output_pm_qos_request",
        "kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start",
        "kernel/bpf/core.c:trace_raw_output_mem_return_failed",
        "kernel/bpf/core.c:trace_raw_output_mem_connect",
        "kernel/bpf/core.c:trace_raw_output_mem_disconnect",
        "kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_map",
        "kernel/bpf/core.c:trace_raw_output_xdp_redirect_template",
        "kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx",
        "kernel/bpf/core.c:trace_raw_output_xdp_exception",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_compact_retry",
        "mm/oom_kill.c:trace_raw_output_reclaim_retry_zone",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate",
        "mm/compaction.c:trace_raw_output_kcompactd_wake_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_defer_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_suitable_template",
        "mm/compaction.c:trace_raw_output_mm_compaction_end",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/migrate.c:trace_raw_output_mm_migrate_pages",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page",
        "mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd",
        "fs/fs-writeback.c:trace_raw_output_writeback_queue_io",
        "fs/fs-writeback.c:trace_raw_output_writeback_work_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/locks.c:trace_raw_output_locks_get_lock_context",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue",
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write",
        "drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip",
        "drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "drivers/ras/ras.c:trace_raw_output_memory_failure_event",
        "net/core/net-traces.c:trace_raw_output_neigh__update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_neigh_update",
        "net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_inet_sock_set_state",
        "net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621952,
      "name": "trace_print_symbols_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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

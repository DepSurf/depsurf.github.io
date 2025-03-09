# Function: <code>simple_read_from_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581155680,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:585",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/libfs.c:simple_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:u32_array_read",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "drivers/regulator/core.c:supply_map_read_file",
        "drivers/char/virtio_console.c:debugfs_read",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/mmc/core/debugfs.c:mmc_ext_csd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581155680,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323728,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:613",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:supply_map_read_file",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/char/virtio_console.c:debugfs_read",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/mmc/core/debugfs.c:mmc_ext_csd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323728,
      "name": "simple_read_from_buffer",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402880,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:621",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:supply_map_read_file",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/char/virtio_console.c:debugfs_read",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/mmc/core/debugfs.c:mmc_ext_csd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402880,
      "name": "simple_read_from_buffer",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458688,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:622",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/char/virtio_console.c:debugfs_read",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/mmc/core/debugfs.c:mmc_ext_csd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458688,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581600736,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:622",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/char/virtio_console.c:debugfs_read",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581600736,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759296,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:622",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/char/virtio_console.c:debugfs_read",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_debugfs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759296,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845824,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:622",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845824,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970432,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:641",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970432,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040976,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "arch/x86/platform/uv/tlb_uv.c:tunables_read",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040976,
      "name": "simple_read_from_buffer",
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276544,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:715",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "arch/x86/platform/uv/tlb_uv.c:tunables_read",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276544,
      "name": "simple_read_from_buffer",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326896,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:717",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326896,
      "name": "simple_read_from_buffer",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582355440,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:720",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355440,
      "name": "simple_read_from_buffer",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675856,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:729",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:trace_min_max_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_status",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675856,
      "name": "simple_read_from_buffer",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216112,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:756",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:trace_min_max_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_status",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/smack/smackfs.c:smk_read_ptrace",
        "security/smack/smackfs.c:smk_read_logging",
        "security/smack/smackfs.c:smk_read_mapped",
        "security/smack/smackfs.c:smk_read_direct",
        "security/smack/smackfs.c:smk_read_doi",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "security/integrity/evm/evm_secfs.c:evm_read_key",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216112,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794144,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:757",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:trace_min_max_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/rv/rv.c:monitoring_on_read_data",
        "kernel/trace/rv/rv.c:monitor_desc_read_data",
        "kernel/trace/rv/rv.c:monitor_enable_read_data",
        "kernel/trace/rv/rv_reactors.c:reacting_on_read_data",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_status",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/smack/smackfs.c:smk_read_ptrace",
        "security/smack/smackfs.c:smk_read_logging",
        "security/smack/smackfs.c:smk_read_mapped",
        "security/smack/smackfs.c:smk_read_direct",
        "security/smack/smackfs.c:smk_read_doi",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "security/integrity/evm/evm_secfs.c:evm_read_key",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583794144,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584011760,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:752",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:trace_min_max_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/rv/rv.c:monitoring_on_read_data",
        "kernel/trace/rv/rv.c:monitor_desc_read_data",
        "kernel/trace/rv/rv.c:monitor_enable_read_data",
        "kernel/trace/rv/rv_reactors.c:reacting_on_read_data",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_status",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/smack/smackfs.c:smk_read_ptrace",
        "security/smack/smackfs.c:smk_read_logging",
        "security/smack/smackfs.c:smk_read_mapped",
        "security/smack/smackfs.c:smk_read_direct",
        "security/smack/smackfs.c:smk_read_doi",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "security/integrity/evm/evm_secfs.c:evm_read_key",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011760,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224080,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:1022",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:cpu_latency_qos_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_subbuf_size_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:trace_min_max_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_max_lat_read",
        "kernel/trace/trace.c:tracing_thresh_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header_page_file",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/rv/rv.c:monitoring_on_read_data",
        "kernel/trace/rv/rv.c:monitor_desc_read_data",
        "kernel/trace/rv/rv.c:monitor_enable_read_data",
        "kernel/trace/rv/rv_reactors.c:reacting_on_read_data",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_str",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_status",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/smack/smackfs.c:smk_read_ptrace",
        "security/smack/smackfs.c:smk_read_logging",
        "security/smack/smackfs.c:smk_read_mapped",
        "security/smack/smackfs.c:smk_read_direct",
        "security/smack/smackfs.c:smk_read_doi",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "security/integrity/evm/evm_secfs.c:evm_read_key",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/opp/debugfs.c:bw_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224080,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493570744,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/mmc/core/block.c:mmc_ext_csd_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493570744,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227115992,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/atags_proc.c:atags_read",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_nsecs_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/mmc/core/block.c:mmc_ext_csd_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "sound/soc/soc-dapm.c:dapm_bias_read_file",
        "sound/soc/soc-dapm.c:dapm_widget_power_read_file",
        "sound/soc/soc-pcm.c:dpcm_state_read_file",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227115992,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287148096,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/proc_powerpc.c:page_map_read",
        "arch/powerpc/kernel/eeh.c:eeh_debugfs_dev_usage",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_read",
        "arch/powerpc/platforms/pseries/lpar.c:vpa_file_read",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_status",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287148096,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273227534,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/mmc/core/block.c:mmc_ext_csd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273227534,
      "name": "simple_read_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582009712,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009712,
      "name": "simple_read_from_buffer",
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947280,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947280,
      "name": "simple_read_from_buffer",
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000992,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000992,
      "name": "simple_read_from_buffer",
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
ssize_t simple_read_from_buffer(void * to, size_t count, loff_t * ppos, const void * from, size_t available)
```

```json
{
  "name": "simple_read_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073968,
      "name": "simple_read_from_buffer",
      "external": true,
      "loc": "fs/libfs.c:646",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:tlbflush_read_file",
        "arch/x86/mm/pkeys.c:init_pkru_read_file",
        "arch/x86/platform/uv/tlb_uv.c:tunables_read",
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/user.c:snapshot_read",
        "kernel/kprobes.c:read_enabled_file_bool",
        "kernel/trace/ftrace.c:ftrace_profile_read",
        "kernel/trace/trace.c:buffer_percent_read",
        "kernel/trace/trace.c:rb_simple_read",
        "kernel/trace/trace.c:trace_options_core_read",
        "kernel/trace/trace.c:trace_options_read",
        "kernel/trace/trace.c:tracing_read_dyn_info",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_total_entries_read",
        "kernel/trace/trace.c:tracing_entries_read",
        "kernel/trace/trace.c:tracing_set_trace_read",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:tracing_readme_read",
        "kernel/trace/trace.c:tracing_cpumask_read",
        "kernel/trace/trace_hwlat.c:hwlat_read",
        "kernel/trace/trace_stack.c:stack_max_size_read",
        "kernel/trace/trace_functions_graph.c:graph_depth_read",
        "kernel/trace/blktrace.c:blk_dropped_read",
        "kernel/trace/trace_events.c:show_header",
        "kernel/trace/trace_events.c:subsystem_filter_read",
        "kernel/trace/trace_events.c:event_id_read",
        "kernel/trace/trace_events.c:system_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "fs/libfs.c:simple_attr_read",
        "fs/libfs.c:simple_transaction_read",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:auxv_read",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/configfs/file.c:configfs_read_file",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/debugfs/file.c:u32_array_read",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/pstore/inode.c:pstore_file_read",
        "fs/efivarfs/file.c:efivarfs_file_read",
        "ipc/mqueue.c:mqueue_read_file",
        "security/inode.c:lsm_read",
        "security/selinux/selinuxfs.c:sel_read_policycap",
        "security/selinux/selinuxfs.c:sel_read_perm",
        "security/selinux/selinuxfs.c:sel_read_class",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_read_avc_hash_stats",
        "security/selinux/selinuxfs.c:sel_read_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_read_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_read_mls",
        "security/selinux/selinuxfs.c:sel_read_policyvers",
        "security/selinux/selinuxfs.c:sel_read_handle_unknown",
        "security/selinux/selinuxfs.c:sel_read_enforce",
        "security/apparmor/apparmorfs.c:attr_read",
        "security/apparmor/apparmorfs.c:rawdata_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:ns_revision_read",
        "security/safesetid/securityfs.c:safesetid_file_read",
        "security/lockdown/lockdown.c:lockdown_read",
        "security/integrity/ima/ima_fs.c:ima_show_measurements_count",
        "security/integrity/ima/ima_fs.c:ima_show_htable_violations",
        "drivers/regulator/core.c:constraint_flags_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file",
        "drivers/mfd/aat2870-core.c:aat2870_reg_read_file",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073968,
      "name": "simple_read_from_buffer",
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
